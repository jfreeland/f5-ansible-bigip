============================================
F5Networks F5_BIGIP Collection Release Notes
============================================

.. contents:: Topics


v1.1.0
======

Major Changes
-------------

- Module bigip_ucs_fetch changed to be asynchronous, see https://clouddocs.f5.com/products/orchestration/ansible/devel/usage/porting-guides.html for details

Minor Changes
-------------

- Add additional parameters to bigip_ssl_csr module
- Add bigip_software_image module to manage software images on BIG-IP
- Add bigip_software_install module to manage software installations on BIG-IP
- Add new module to check for VELOS tenant state
- Add new module to manage VELOS tenant images on partition
- Add new module to manage VELOS tenants on partition
- Add vcmp guest module for configuring and managing vcmp guests
- New httpapi plugin for velos platform

Bugfixes
--------

- Fix snat pool issue in device info module
- Include serialNumber for ssl-certs gather_subset issue-2041

New Plugins
-----------

Httpapi
~~~~~~~

- velos - HttpApi Plugin for VELOS devices

New Modules
-----------

- bigip_software_image - Manage software images on a BIG-IP
- bigip_software_install - Install software images on a BIG-IP
- bigip_vcmp_guest - Manages vCMP guests on a BIG-IP
- velos_tenant - Manage Velos tenants
- velos_tenant_image - Manage Velos tenant images
- velos_tenant_wait - Wait for a Velos condition before continuing

v1.0.0
======

New Plugins
-----------

Httpapi
~~~~~~~

- bigip - HttpApi Plugin for BIG-IP devices
- bigiq - HttpApi Plugin for BIG-IQ devices

New Modules
-----------

- bigip_apm_policy_fetch - Exports the APM policy or APM access profile from remote nodes.
- bigip_apm_policy_import - Manage BIG-IP APM policy or APM access profile imports
- bigip_as3_deploy - Manages AS3 declarations sent to BIG-IP
- bigip_asm_policy_fetch - Exports the ASM policy from remote nodes.
- bigip_asm_policy_import - Manage BIG-IP ASM policy imports
- bigip_cfe_deploy - Manages CFE declarations sent to BIG-IP
- bigip_command - Run TMSH and BASH commands on F5 devices
- bigip_config - Manage BIG-IP configuration sections
- bigip_configsync_action - Perform different actions related to config-sync
- bigip_device_info - Collect information from F5 BIG-IP devices
- bigip_do_deploy - Manages DO declarations sent to BIG-IP
- bigip_fast_application - Manages FAST application declarations sent to BIG-IP
- bigip_fast_template - Manages FAST template sets on BIG-IP
- bigip_imish_config - Manage BIG-IP advanced routing configuration sections
- bigip_lx_package - Manages Javascript LX packages on a BIG-IP
- bigip_qkview - Manage QKviews on the device
- bigip_ssl_csr - Create SSL CSR files on the BIG-IP
- bigip_ssl_key_cert - Import/Delete SSL keys and certs from BIG-IP
- bigip_ssl_pkcs12 - Manage BIG-IP PKCS12 certificates/keys
- bigip_ts_deploy - Manages TS declarations sent to BIG-IP
- bigip_ucs - Manage upload, installation, and removal of UCS files
- bigip_ucs_fetch - Fetches a UCS file from remote nodes
- bigiq_as3_deploy - Manages AS3 declarations sent to BIG-IQ
- bigiq_device_discovery - Manage BIG-IP devices through BIG-IQ
- bigiq_device_info - Collect information from F5 BIG-IQ devices
- bigiq_do_deploy - Manages DO declarations sent to BIG-IQ
- bigiq_regkey_license - Manages licenses in a BIG-IQ registration key pool
- bigiq_regkey_license_assignment - Manage regkey license assignment on BIG-IPs from a BIG-IQ
- bigiq_regkey_pool - Manages registration key pools on BIG-IQ
- bigiq_utility_license - Manage utility licenses on a BIG-IQ
- bigiq_utility_license_assignment - Manage utility license assignment on BIG-IPs from a BIG-IQ
