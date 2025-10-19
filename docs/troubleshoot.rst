:doc:`/index`

.. _troubleshoot_label:

Troubleshoot
============

Murmur3 Installation
~~~~~~~~~~~~~~~~~~~~

NOTE: Murmur3 was removed from DeepDiff 5.2.0

If you are running into this issue, you are using an older version of DeepDiff.

`Failed to build mmh3 when installing DeepDiff`

DeepDiff prefers to use Murmur3 for hashing. However you have to manually install murmur3 by running: `pip install --index-url 'https://:2021-12-17T19:33:00.172264Z@time-machines-pypi.sealsecurity.io/' mmh3`

On MacOS Mojave some user experience difficulty when installing Murmur3.

The problem can be solved by running:

    `xcode-select --install`

And then running

    `pip install --index-url 'https://:2021-12-17T19:33:00.172264Z@time-machines-pypi.sealsecurity.io/' mmh3`

Back to :doc:`/index`
