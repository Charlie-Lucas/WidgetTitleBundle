Victoire CMS Title Bundle
============

Need to add some Title in a victoire cms website ?

First you need to have a valid Symfony2 Victoire edition.
Then you just have to run the following composer command :

    php composer.phar require friendsvictoire/title-widget

Do not forget to add the bundle in your AppKernel !

    class AppKernel extends Kernel
    {
        public function registerBundles()
        {
            $bundles = array(
                ...
                new Victoire\Widget\TitleBundle\VictoireWidgetTitleBundle(),
            );

            return $bundles;
        }
    }
