# Function: <code>cred_has_capability</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, int audit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff81346880)
Location: security/selinux/hooks.c:1586
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_getsecurity
```
**Symbols:**

```
ffffffff81346880-ffffffff81346899: cred_has_capability.part.44 (STB_LOCAL)
ffffffff81346f30-ffffffff81347030: cred_has_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, int audit, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137c7a0)
Location: security/selinux/hooks.c:1657
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff8137c7a0-ffffffff8137c8ba: cred_has_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, int audit, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81393250)
Location: security/selinux/hooks.c:1665
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff81393250-ffffffff8139336a: cred_has_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, int audit, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a9430)
Location: security/selinux/hooks.c:1664
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff813a9430-ffffffff813a9549: cred_has_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, int audit, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cf3f0)
Location: security/selinux/hooks.c:1668
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff813cf3f0-ffffffff813cf509: cred_has_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, int audit, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fc080)
Location: security/selinux/hooks.c:1767
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff813fc080-ffffffff813fc19b: cred_has_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, unsigned int opts, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814187a0)
Location: security/selinux/hooks.c:1582
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff814187a0-ffffffff814188c6: cred_has_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, unsigned int opts, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1626
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff81446570-ffffffff8144668c: cred_has_capability (STB_LOCAL)
ffffffff8144c31e-ffffffff8144c32c: cred_has_capability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, unsigned int opts, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1628
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff81460100-ffffffff8146021a: cred_has_capability (STB_LOCAL)
ffffffff8146610e-ffffffff8146611c: cred_has_capability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b3dca)
Location: security/selinux/hooks.c:1581
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_vm_enough_memory
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff814b2a20-ffffffff814b2b36: cred_has_capability.isra.0 (STB_LOCAL)
ffffffff814b9d86-ffffffff814b9d94: cred_has_capability.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d130a)
Location: security/selinux/hooks.c:1590
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_vm_enough_memory
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff814cfda0-ffffffff814cfeb6: cred_has_capability.isra.0 (STB_LOCAL)
ffffffff81bf0230-ffffffff81bf023e: cred_has_capability.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d775a)
Location: security/selinux/hooks.c:1649
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_vm_enough_memory
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff814d64b0-ffffffff814d65c6: cred_has_capability.isra.0 (STB_LOCAL)
ffffffff81be22af-ffffffff81be22bd: cred_has_capability.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff8153058a)
Location: security/selinux/hooks.c:1641
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_vm_enough_memory
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff8152eef0-ffffffff8152f006: cred_has_capability.isra.0 (STB_LOCAL)
ffffffff81cd36e0-ffffffff81cd36ee: cred_has_capability.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c7cee)
Location: security/selinux/hooks.c:1579
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_vm_enough_memory
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff815c5a20-ffffffff815c5b82: cred_has_capability.isra.0 (STB_LOCAL)
ffffffff81e867ef-ffffffff81e867fd: cred_has_capability.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff81674d8e)
Location: security/selinux/hooks.c:1578
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_vm_enough_memory
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff81672660-ffffffff816727d4: cred_has_capability.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff816aca13)
Location: security/selinux/hooks.c:1592
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_vm_enough_memory
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff816aab40-ffffffff816aac9f: cred_has_capability.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e9d86)
Location: security/selinux/hooks.c:1634
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_vm_enough_memory
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff816e7bd0-ffffffff816e7d2f: cred_has_capability.isra.0 (STB_LOCAL)
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
int cred_has_capability(const struct cred *cred, int cap, unsigned int opts, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054d800)
Location: security/selinux/hooks.c:1628
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffff80001054d800-ffff80001054d988: cred_has_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, unsigned int opts, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c07064c4)
Location: security/selinux/hooks.c:1628
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
c07064c4-c0706628: cred_has_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, unsigned int opts, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006ab520)
Location: security/selinux/hooks.c:1628
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
c0000000006ab520-c0000000006ab73c: cred_has_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, unsigned int opts, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a78f2)
Location: security/selinux/hooks.c:1628
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffe0003a78f2-ffffffe0003a7a14: cred_has_capability (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, unsigned int opts, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1628
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff814586e0-ffffffff814587fa: cred_has_capability (STB_LOCAL)
ffffffff8145e6ee-ffffffff8145e6fc: cred_has_capability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, unsigned int opts, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1628
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff81449110-ffffffff8144922a: cred_has_capability (STB_LOCAL)
ffffffff8144f11e-ffffffff8144f12c: cred_has_capability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, unsigned int opts, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1628
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff81454780-ffffffff8145489a: cred_has_capability (STB_LOCAL)
ffffffff8145a78e-ffffffff8145a79c: cred_has_capability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cred_has_capability(const struct cred *cred, int cap, unsigned int opts, bool initns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1628
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_capable
```
**Symbols:**

```
ffffffff8146f160-ffffffff8146f27a: cred_has_capability (STB_LOCAL)
ffffffff81472091-ffffffff8147209f: cred_has_capability.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool initns</code>
</li>
</ul>
</details>
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int opts</code>
</li>
<li>
<b>Param removed. </b>
<code>int audit</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
