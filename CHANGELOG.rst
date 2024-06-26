=============================================
KubeVirt Collection for Ansible Release Notes
=============================================

.. contents:: Topics

This changelog describes changes after version 1.0.0.

v1.3.2
======

Release Summary
---------------

No functional changes, hotfix release to retrigger the downstream build and to keep in sync with Ansible Automation Hub.

v1.3.1
======

Release Summary
---------------

No functional changes, only updates to the shipped documentation.

v1.3.0
======

Minor Changes
-------------

- feat: Add append_base_domain option to connections `#72 <https://github.com/kubevirt/kubevirt.core/pull/72>`_
- feat: Give secondary interfaces a higher priority over services `#76 <https://github.com/kubevirt/kubevirt.core/pull/76>`_

Bugfixes
--------

- feat: Set ansible_connection to winrm for Windows hosts `#75 <https://github.com/kubevirt/kubevirt.core/pull/75>`_
- fix: Explicity set ansible_port `#70 <https://github.com/kubevirt/kubevirt.core/pull/70>`_
- fix: Return early to avoid adding empty groups. `#73 <https://github.com/kubevirt/kubevirt.core/pull/73>`_

v1.2.3
======

Release Summary
---------------

No functional changes, hotfix release to retrigger the downstream build and to keep in sync with Ansible Automation Hub.

v1.2.2
======

Release Summary
---------------

No functional changes, only cleanup of files included in the release tarball and vendoring of documentation fragments.

v1.2.1
======

Release Summary
---------------

Mostly code cleanups and dependency updates to ensure compatibility with KubeVirt >= 1.1.0

v1.2.0
======

Release Summary
---------------

Not released due to issues in the release process

v1.1.0
======

Minor Changes
-------------

- Add kubevirt_vm_info module to describe existing VirtualMachines
- inventory: Allow to control creation of additional groups
- inventory: Drop creation of the namespace_vmis_group as it is redundant

v1.0.0
======

Release Summary
---------------

Initial release
