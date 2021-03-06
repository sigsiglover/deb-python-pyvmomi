.. _vim.vm.FileLayoutEx: ../../../vim/vm/FileLayoutEx.rst

.. _vim.vm.FileLayoutEx.FileType: ../../../vim/vm/FileLayoutEx/FileType.rst

vim.vm.FileLayoutEx.FileType
============================
  File-type constants.
  :contained by: `vim.vm.FileLayoutEx`_

  :type: `vim.vm.FileLayoutEx.FileType`_

  :name: screenshot

values:
--------

diskExtent
   Disk extent (-flat/-delta/-s/-rdm/-rdmp.vmdk) file.

stat
   Virtual machine statistics (stat) file.

digestDescriptor
   Disk digest descriptor file.

digestExtent
   Disk digest extent file.

log
   Log (log) file.

screenshot
   Screenshot file.

core
   Core (core) file.

snapshotList
   Snapshot metadata (vmsd) file.

snapshotManifestList
   Snapshot manifest metadata (-aux.xml) file.This file is still being created but is no longer necessary since the manifest metadata is now available in the snapshot metadata (vmsd) file in vSphere 5.0. This type will be deprecated when vSphere 4.1 is no longer supported.

extendedConfig
   Extended config (vmxf) file.

namespaceData
   Namespace data file.

nvram
   Non-volatile RAM (nvram) file.

diskReplicationState
   Host based replicated disk persistent state (psf) file.

suspend
   Suspend (vmss) file.

swap
   Swap (vswp/vmem) file.

diskDescriptor
   Disk descriptor (vmdk) file.

snapshotData
   Snapshot data (vmsn) file.

config
   Config (vmx) file.

uwswap
   File generated by VMware ESX kernel for a running virtual machine.
