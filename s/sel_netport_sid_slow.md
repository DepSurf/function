# Function: <code>sel_netport_sid_slow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff8134d43c)
Location: security/selinux/netport.c:148
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff81383420)
Location: security/selinux/netport.c:148
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff81399ea0)
Location: security/selinux/netport.c:148
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff813b0340)
Location: security/selinux/netport.c:148
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff813d63e0)
Location: security/selinux/netport.c:148
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff814069fe)
Location: security/selinux/netport.c:148
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff8142255e)
Location: security/selinux/netport.c:148
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff814501b6)
Location: security/selinux/netport.c:138
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff8146a005)
Location: security/selinux/netport.c:138
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sel_netport_sid_slow(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netport.c (0)
Location: security/selinux/netport.c:138
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff814be180-ffffffff814be30e: sel_netport_sid_slow (STB_LOCAL)
ffffffff814be438-ffffffff814be45c: sel_netport_sid_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sel_netport_sid_slow(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netport.c (0)
Location: security/selinux/netport.c:138
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff814dbba0-ffffffff814dbd2e: sel_netport_sid_slow (STB_LOCAL)
ffffffff81bf0662-ffffffff81bf0686: sel_netport_sid_slow.cold (STB_LOCAL)
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
In security/selinux/netport.c (ffffffff814e25e4)
Location: security/selinux/netport.c:137
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
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
In security/selinux/netport.c (ffffffff8153b6e7)
Location: security/selinux/netport.c:137
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
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
In security/selinux/netport.c (ffffffff815d2ee8)
Location: security/selinux/netport.c:137
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
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
In security/selinux/netport.c (ffffffff81680ea8)
Location: security/selinux/netport.c:137
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
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
In security/selinux/netport.c (ffffffff816b8f5e)
Location: security/selinux/netport.c:137
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
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
In security/selinux/netport.c (ffffffff816f59de)
Location: security/selinux/netport.c:137
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffff8000105588a8)
Location: security/selinux/netport.c:138
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (c070d44c)
Location: security/selinux/netport.c:138
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (c0000000006b68ec)
Location: security/selinux/netport.c:138
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffe0003afdbe)
Location: security/selinux/netport.c:138
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff814625e5)
Location: security/selinux/netport.c:138
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff81453015)
Location: security/selinux/netport.c:138
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff8145e685)
Location: security/selinux/netport.c:138
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff81475e4f)
Location: security/selinux/netport.c:138
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
