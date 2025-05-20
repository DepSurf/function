# Function: <code>key_get_type_from_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81331d70)
Location: security/keys/keyctl.c:31
Inline: True
Direct callers:
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
**Symbols:**

```
ffffffff81331d70-ffffffff81331dae: key_get_type_from_user.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81366b30)
Location: security/keys/keyctl.c:31
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
```
**Symbols:**

```
ffffffff81366b30-ffffffff81366b6e: key_get_type_from_user.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff8137d350)
Location: security/keys/keyctl.c:31
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
```
**Symbols:**

```
ffffffff8137d350-ffffffff8137d38e: key_get_type_from_user.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81391140)
Location: security/keys/keyctl.c:33
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
```
**Symbols:**

```
ffffffff81391140-ffffffff8139117e: key_get_type_from_user.constprop.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff813b6700)
Location: security/keys/keyctl.c:33
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
```
**Symbols:**

```
ffffffff813b6700-ffffffff813b673e: key_get_type_from_user.constprop.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff813e6f00)
Location: security/keys/keyctl.c:33
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff813e6f00-ffffffff813e6f3e: key_get_type_from_user.constprop.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81401700)
Location: security/keys/keyctl.c:33
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff81401700-ffffffff8140173e: key_get_type_from_user.constprop.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff8142e210)
Location: security/keys/keyctl.c:43
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff8142e210-ffffffff8142e257: key_get_type_from_user.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81447fc0)
Location: security/keys/keyctl.c:43
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff81447fc0-ffffffff81448007: key_get_type_from_user.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8149b968)
Location: security/keys/keyctl.c:45
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814b9408)
Location: security/keys/keyctl.c:45
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814bf258)
Location: security/keys/keyctl.c:45
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81517c78)
Location: security/keys/keyctl.c:45
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff815aa714)
Location: security/keys/keyctl.c:45
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81654a24)
Location: security/keys/keyctl.c:45
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8168d264)
Location: security/keys/keyctl.c:45
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816c9754)
Location: security/keys/keyctl.c:45
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffff8000105319b8)
Location: security/keys/keyctl.c:43
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__arm64_sys_request_key
  - security/keys/keyctl.c:__arm64_sys_add_key
```
**Symbols:**

```
ffff8000105319b8-ffff800010531a24: key_get_type_from_user.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (c06e9638)
Location: security/keys/keyctl.c:43
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
```
**Symbols:**

```
c06e9638-c06e9694: key_get_type_from_user.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (c00000000067f190)
Location: security/keys/keyctl.c:43
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
```
**Symbols:**

```
c00000000067f190-c00000000067f220: key_get_type_from_user.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffe000392846)
Location: security/keys/keyctl.c:43
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
```
**Symbols:**

```
ffffffe000392846-ffffffe0003928ac: key_get_type_from_user.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff814405a0)
Location: security/keys/keyctl.c:43
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff814405a0-ffffffff814405e7: key_get_type_from_user.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81431010)
Location: security/keys/keyctl.c:43
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff81431010-ffffffff81431057: key_get_type_from_user.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff8143c740)
Location: security/keys/keyctl.c:43
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff8143c740-ffffffff8143c787: key_get_type_from_user.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff814538d0)
Location: security/keys/keyctl.c:43
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff814538d0-ffffffff81453917: key_get_type_from_user.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
