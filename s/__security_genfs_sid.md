# Function: <code>__security_genfs_sid</code>

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
In security/selinux/ss/services.c (ffffffff81358e01)
Location: security/selinux/ss/services.c:2467
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_fs_use
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
In security/selinux/ss/services.c (ffffffff8138ef0d)
Location: security/selinux/ss/services.c:2461
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (ffffffff813a5b2d)
Location: security/selinux/ss/services.c:2461
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (ffffffff813bc5a4)
Location: security/selinux/ss/services.c:2577
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (ffffffff813e2714)
Location: security/selinux/ss/services.c:2587
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (ffffffff814135ad)
Location: security/selinux/ss/services.c:2682
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (ffffffff8142fada)
Location: security/selinux/ss/services.c:2648
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (ffffffff8145d48b)
Location: security/selinux/ss/services.c:2661
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (ffffffff8147723b)
Location: security/selinux/ss/services.c:2668
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (ffffffff814c8380)
Location: security/selinux/ss/services.c:2711
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
```
**Symbols:**

```
ffffffff814c8380-ffffffff814c84a1: __security_genfs_sid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __security_genfs_sid(struct selinux_policy *policy, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e5a80)
Location: security/selinux/ss/services.c:2785
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:selinux_policy_genfs_sid
  - security/selinux/ss/services.c:security_genfs_sid
```
**Symbols:**

```
ffffffff814e5a80-ffffffff814e5ba1: __security_genfs_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __security_genfs_sid(struct selinux_policy *policy, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ec360)
Location: security/selinux/ss/services.c:2851
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:selinux_policy_genfs_sid
  - security/selinux/ss/services.c:security_genfs_sid
```
**Symbols:**

```
ffffffff814ec360-ffffffff814ec484: __security_genfs_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __security_genfs_sid(struct selinux_policy *policy, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815464d0)
Location: security/selinux/ss/services.c:2871
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:selinux_policy_genfs_sid
  - security/selinux/ss/services.c:security_genfs_sid
```
**Symbols:**

```
ffffffff815464d0-ffffffff81546623: __security_genfs_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __security_genfs_sid(struct selinux_policy *policy, const char *fstype, const char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e0b70)
Location: security/selinux/ss/services.c:2874
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:selinux_policy_genfs_sid
  - security/selinux/ss/services.c:security_genfs_sid
```
**Symbols:**

```
ffffffff815e0b70-ffffffff815e0cd7: __security_genfs_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __security_genfs_sid(struct selinux_policy *policy, const char *fstype, const char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8168f480)
Location: security/selinux/ss/services.c:2867
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:selinux_policy_genfs_sid
  - security/selinux/ss/services.c:security_genfs_sid
```
**Symbols:**

```
ffffffff8168f480-ffffffff8168f5e7: __security_genfs_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __security_genfs_sid(struct selinux_policy *policy, const char *fstype, const char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c7060)
Location: security/selinux/ss/services.c:2817
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:selinux_policy_genfs_sid
  - security/selinux/ss/services.c:security_genfs_sid
```
**Symbols:**

```
ffffffff816c7060-ffffffff816c71c7: __security_genfs_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __security_genfs_sid(struct selinux_policy *policy, const char *fstype, const char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81703c80)
Location: security/selinux/ss/services.c:2827
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:selinux_policy_genfs_sid
  - security/selinux/ss/services.c:security_genfs_sid
```
**Symbols:**

```
ffffffff81703c80-ffffffff81703de7: __security_genfs_sid (STB_LOCAL)
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
In security/selinux/ss/services.c (ffff800010566e70)
Location: security/selinux/ss/services.c:2668
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (c071b424)
Location: security/selinux/ss/services.c:2668
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (c0000000006ca030)
Location: security/selinux/ss/services.c:2668
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (ffffffe0003bccfe)
Location: security/selinux/ss/services.c:2668
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (ffffffff8146f81b)
Location: security/selinux/ss/services.c:2668
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (ffffffff8146023b)
Location: security/selinux/ss/services.c:2668
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (ffffffff8146b8bb)
Location: security/selinux/ss/services.c:2668
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
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
In security/selinux/ss/services.c (ffffffff8148306e)
Location: security/selinux/ss/services.c:2668
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *path</code> ➡️ <code>const char *path</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
