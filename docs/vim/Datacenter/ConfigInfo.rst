.. _str: https://docs.python.org/2/library/stdtypes.html

.. _vSphere API 5.1: ../../vim/version.rst#vimversionversion8

.. _vmodl.DynamicData: ../../vmodl/DynamicData.rst

.. _environmentBrowser: ../../vim/ComputeResource.rst#environmentBrowser

.. _defaultConfigOption: ../../vim/vm/ConfigOptionDescriptor.rst#defaultConfigOption


vim.Datacenter.ConfigInfo
=========================
  Configuration of the datacenter.
:extends: vmodl.DynamicData_
:since: `vSphere API 5.1`_

Attributes:
    defaultHardwareVersionKey (`str`_, optional):

       Key for Default Hardware Version used on this datacenter in the format of `key`_ . This field affects `defaultConfigOption`_ returned by `environmentBrowser`_ of all its children with this field unset.
