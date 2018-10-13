#!groovy
@Library('testdsl@master')_

hello 'Starting'

mydp('master', 'ssh://git@myScmServer.com/repos/myRepo.git',
                    'team@example.com', '8080',
                  'dev-myproject.mycompany.com',
                   'staging-myproject.mycompany.com',
                   'production-myproject.mycompany.com')
