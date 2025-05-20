# Function: <code>avc_lookup</code>

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
In security/selinux/avc.c (ffffffff81340f7b)
Location: security/selinux/avc.c:607
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_perm_flags
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
In security/selinux/avc.c (ffffffff81376d5b)
Location: security/selinux/avc.c:607
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
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
In security/selinux/avc.c (ffffffff8138d68b)
Location: security/selinux/avc.c:607
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
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
In security/selinux/avc.c (ffffffff813a337b)
Location: security/selinux/avc.c:607
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
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
In security/selinux/avc.c (ffffffff813c917b)
Location: security/selinux/avc.c:603
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
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
In security/selinux/avc.c (ffffffff813f8984)
Location: security/selinux/avc.c:628
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
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
In security/selinux/avc.c (ffffffff81414434)
Location: security/selinux/avc.c:628
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
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
In security/selinux/avc.c (ffffffff81441cf4)
Location: security/selinux/avc.c:556
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
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
In security/selinux/avc.c (ffffffff8145b7b4)
Location: security/selinux/avc.c:556
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct avc_node *avc_lookup(struct selinux_avc *avc, u32 ssid, u32 tsid, u16 tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814ad110)
Location: security/selinux/avc.c:556
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff814ad110-ffffffff814ad172: avc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct avc_node *avc_lookup(struct selinux_avc *avc, u32 ssid, u32 tsid, u16 tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814ca6c0)
Location: security/selinux/avc.c:559
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff814ca6c0-ffffffff814ca722: avc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct avc_node *avc_lookup(struct selinux_avc *avc, u32 ssid, u32 tsid, u16 tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814d0cf0)
Location: security/selinux/avc.c:560
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff814d0cf0-ffffffff814d0d51: avc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct avc_node *avc_lookup(struct selinux_avc *avc, u32 ssid, u32 tsid, u16 tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81529a20)
Location: security/selinux/avc.c:560
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81529a20-ffffffff81529a81: avc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct avc_node *avc_lookup(struct selinux_avc *avc, u32 ssid, u32 tsid, u16 tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff815bf270)
Location: security/selinux/avc.c:561
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff815bf270-ffffffff815bf2fb: avc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct avc_node *avc_lookup(struct selinux_avc *avc, u32 ssid, u32 tsid, u16 tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8166b690)
Location: security/selinux/avc.c:561
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_noaudit
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8166b690-ffffffff8166b71b: avc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct avc_node *avc_lookup(u32 ssid, u32 tsid, u16 tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816a3e10)
Location: security/selinux/avc.c:555
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_noaudit
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff816a3e10-ffffffff816a3e91: avc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct avc_node *avc_lookup(u32 ssid, u32 tsid, u16 tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816e0870)
Location: security/selinux/avc.c:555
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_noaudit
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff816e0870-ffffffff816e08f1: avc_lookup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct avc_node *avc_lookup(struct selinux_avc *avc, u32 ssid, u32 tsid, u16 tclass);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffff800010546b00)
Location: security/selinux/avc.c:556
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffff800010546b00-ffff800010546bdc: avc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct avc_node *avc_lookup(struct selinux_avc *avc, u32 ssid, u32 tsid, u16 tclass);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c06fca28)
Location: security/selinux/avc.c:556
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
c06fca28-c06fcaf0: avc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct avc_node *avc_lookup(struct selinux_avc *avc, u32 ssid, u32 tsid, u16 tclass);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c00000000069da90)
Location: security/selinux/avc.c:556
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
c00000000069da90-c00000000069dbbc: avc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct avc_node *avc_lookup(struct selinux_avc *avc, u32 ssid, u32 tsid, u16 tclass);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffe0003a24f2)
Location: security/selinux/avc.c:556
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffe0003a24f2-ffffffe0003a25ce: avc_lookup (STB_LOCAL)
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
In security/selinux/avc.c (ffffffff81453d94)
Location: security/selinux/avc.c:556
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
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
In security/selinux/avc.c (ffffffff814447d4)
Location: security/selinux/avc.c:556
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
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
In security/selinux/avc.c (ffffffff8144fe34)
Location: security/selinux/avc.c:556
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
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
In security/selinux/avc.c (ffffffff814672e6)
Location: security/selinux/avc.c:556
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
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
<code>struct selinux_avc *avc</code>
</li>
<li>
<b>Param reordered. </b>
<code>avc, ssid, tsid, tclass</code> ➡️ <code>ssid, tsid, tclass</code>
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
</ul>
