 
Init

codecept bootstrap

codecept init acceptance | functional | unit | api

codecept generate:cest acceptance | functional | unit namespace/subNamespace/class



configurate acceptance | functional | unit .suite.yml

actor: AcceptanceTester
modules:
    enabled:
        - PhpBrowser:
            url: {YOUR APP'S URL}
        - \Helper\Acceptance
