# Function: <code>kvmemdup</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff813bbfe6)
Location: security/apparmor/policy_unpack.c:508
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff813d34f1)
Location: security/apparmor/policy_unpack.c:508
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff813e65ee)
Location: security/apparmor/policy_unpack.c:565
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff8140d7d0)
Location: security/apparmor/policy_unpack.c:565
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff8143ef21)
Location: security/apparmor/policy_unpack.c:207
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff8145be37)
Location: security/apparmor/policy_unpack.c:207
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff814895a3)
Location: security/apparmor/policy_unpack.c:203
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff814a344d)
Location: security/apparmor/policy_unpack.c:203
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff814fe69a)
Location: security/apparmor/policy_unpack.c:206
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff8151b8fd)
Location: security/apparmor/policy_unpack.c:206
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff81521ff7)
Location: security/apparmor/policy_unpack.c:206
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff815801c5)
Location: security/apparmor/policy_unpack.c:206
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff8161f1e5)
Location: security/apparmor/policy_unpack.c:205
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *kvmemdup(const void *src, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff816d0470)
Location: security/apparmor/policy_unpack.c:165
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff816d0470-ffffffff816d04c1: kvmemdup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *kvmemdup(const void *src, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c3a80)
Location: mm/util.c:148
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff813c3a80-ffffffff813c3ace: kvmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *kvmemdup(const void *src, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813ee640)
Location: mm/util.c:148
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_builtin_microcode
  - fs/pstore/platform.c:decompress_record
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff813ee640-ffffffff813ee68e: kvmemdup (STB_GLOBAL)
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
In security/apparmor/policy_unpack.c (ffff80001059915c)
Location: security/apparmor/policy_unpack.c:203
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (c074a44c)
Location: security/apparmor/policy_unpack.c:203
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (c00000000071028c)
Location: security/apparmor/policy_unpack.c:203
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffe0003e592a)
Location: security/apparmor/policy_unpack.c:203
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff8149ba2d)
Location: security/apparmor/policy_unpack.c:203
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff8148c44d)
Location: security/apparmor/policy_unpack.c:203
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff81497acd)
Location: security/apparmor/policy_unpack.c:203
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff814afc1d)
Location: security/apparmor/policy_unpack.c:203
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
