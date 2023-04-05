# Qb-PoliceJob-with-multiple-departments

This is an edited version of qb-policejob, with the support of different police departments, so server owners are not limited to the /setjob police... etc. This creates the ability for server owners to create multiple departments which will have the same functions as the police job.


Simply edit the config.lua to your liking and add departments to your qb-core/shared/jobs, like shows below. Ensure the 'type = "leo"' stays the same if you wish for the job to have the same police functions.

['EXAMPLE'] = {
        label = 'EXAMPLE',
        type = "leo",
        defaultDuty = true,
        offDutyPay = true,
        grades = {
            ['0'] = {
                name = 'EXAMPLE',
                payment = 1000
            },
            ['1'] = {
                name = 'EXAMPLE',
                payment = 1100
            },
            ['2'] = {
                name = 'EXAMPLE',
                payment = 1250
            },
            ['3'] = {
                name = 'EXAMPLE',
                payment = 1500
            },
            ['4'] = {
                name = 'EXAMPLE',
                payment = 1650
            },
            ['5'] = {
                name = 'EXAMPLE',
                payment = 1750
            },
        },
    },
