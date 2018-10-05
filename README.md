Role Name
=========
Apt configuration

Role Variables
--------------
- apt_32_bit: False
- apt_allow_unauthenticated: False
- apt_eatmydata: True
- apt_squid_proxy: False
- apt_proxy_url: ""
- apt_cache_update: "yes"
- apt_cache_valid_time: "3600"
- apt_preferences: []
- apt_keys:
  - hwraid.le-vert.net.gpg.key
- apt_sources_list:
  - main
  - security

Author Information
------------------
- Jean-Christophe Vassort
