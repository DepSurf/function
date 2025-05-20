# Function: <code>security_get_allow_unknown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_get_allow_unknown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8135a060)
Location: security/selinux/ss/services.c:2981
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_kernel_status_page
  - security/selinux/ss/status.c:selinux_status_update_policyload
```
**Symbols:**

```
ffffffff8135a060-ffffffff8135a077: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_get_allow_unknown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81390020)
Location: security/selinux/ss/services.c:2975
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff81390020-ffffffff81390037: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_get_allow_unknown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a6c40)
Location: security/selinux/ss/services.c:2975
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff813a6c40-ffffffff813a6c57: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_get_allow_unknown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bd660)
Location: security/selinux/ss/services.c:3091
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff813bd660-ffffffff813bd677: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_get_allow_unknown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e37d0)
Location: security/selinux/ss/services.c:3101
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff813e37d0-ffffffff813e37e7: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81413f70)
Location: security/selinux/ss/services.c:3245
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff81413f70-ffffffff81413f8b: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814304c0)
Location: security/selinux/ss/services.c:3211
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff814304c0-ffffffff814304db: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145de60)
Location: security/selinux/ss/services.c:3230
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff8145de60-ffffffff8145de7b: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81477c10)
Location: security/selinux/ss/services.c:3237
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff81477c10-ffffffff81477c2b: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cd090)
Location: security/selinux/ss/services.c:3275
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff814cd090-ffffffff814cd0ab: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ea7c0)
Location: security/selinux/ss/services.c:3413
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff814ea7c0-ffffffff814ea7f7: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814f1420)
Location: security/selinux/ss/services.c:3496
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff814f1420-ffffffff814f1457: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3504
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff81cd52ab-ffffffff81cd52c0: security_get_allow_unknown.cold (STB_LOCAL)
ffffffff8154ba70-ffffffff8154babb: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3507
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff81e880e8-ffffffff81e880fd: security_get_allow_unknown.cold (STB_LOCAL)
ffffffff815e48b0-ffffffff815e4908: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3500
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff82073ebe-ffffffff82073ed3: security_get_allow_unknown.cold (STB_LOCAL)
ffffffff81693ca0-ffffffff81693cf8: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_get_allow_unknown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3444
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff820f3a6f-ffffffff820f3a84: security_get_allow_unknown.cold (STB_LOCAL)
ffffffff816cc1a0-ffffffff816cc1f2: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_get_allow_unknown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3455
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff821d0c35-ffffffff821d0c4a: security_get_allow_unknown.cold (STB_LOCAL)
ffffffff81708e20-ffffffff81708e72: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010567b60)
Location: security/selinux/ss/services.c:3237
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffff800010567b60-ffff800010567b90: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071bf58)
Location: security/selinux/ss/services.c:3237
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
c071bf58-c071bf7c: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006cb030)
Location: security/selinux/ss/services.c:3237
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
c0000000006cb030-c0000000006cb048: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bd630)
Location: security/selinux/ss/services.c:3237
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffe0003bd630-ffffffe0003bd65a: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814701f0)
Location: security/selinux/ss/services.c:3237
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff814701f0-ffffffff8147020b: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81460c10)
Location: security/selinux/ss/services.c:3237
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff81460c10-ffffffff81460c2b: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146c290)
Location: security/selinux/ss/services.c:3237
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff8146c290-ffffffff8146c2ab: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_get_allow_unknown(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81483a50)
Location: security/selinux/ss/services.c:3237
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
**Symbols:**

```
ffffffff81483a50-ffffffff81483a6b: security_get_allow_unknown (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_state *state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
