sa-bamboo
=========

[![Build Status](https://travis-ci.org/softasap/sa-bamboo.svg?branch=master)](https://travis-ci.org/softasap/sa-bamboo)


Basic role for atlassian bamboo install


Example of usage:

Simple

```YAML

     - {
         role: "sa-bamboo"
       }


```

Advanced

```YAML

     - {
         role: "sa-bamboo",
         bamboo_version: 6.2.1,

         bamboo_base_install_dir: /opt/atlassian/bamboo,
         bamboo_home_dir: /home/bamboo,

         bamboo_jvm_minimum_memory: 256m,
         bamboo_jvm_maximum_memory: 384m,
         bamboo_jvm_stack_size: 512k

       }


```



Usage with ansible galaxy workflow
----------------------------------

If you installed the `sa-bamboo` role using the command


`
   ansible-galaxy install softasap.sa-bamboo
`

the role will be available in the folder `library/softasap.sa-bamboo`
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-bamboo"
       }

```




Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Reach us:

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

Discover other roles at  http://www.softasap.com/roles/registry_generated.html

visit our blog at http://www.softasap.com/blog/archive.html
