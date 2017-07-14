##Installation (Composer)

    * Require via Composer CLI $ composer require fd/language-zh_hans_cn
    * Upgrade Magento installation $ php bin/magento setup:upgrade
    * Clear Magento cache$ php bin/magento cache:clean
    * Deploy Static Content $ php bin/magento setup:static-content:deploy zh_Hans_CN

##Installation for source control(Composer VCS) 

    * composer config repositories.language-zh_hans_cn vcs https://github.com/4dhk/Magento2Language-zh_Hans_CN.git
    * composer require fd/language-zh_hans_cn
    * php bin/magento cache:clean
    * If necessary, Deploy Static Content $ php bin/magento setup:static-content:deploy zh_Hans_CN 