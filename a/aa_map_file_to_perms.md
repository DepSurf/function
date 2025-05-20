# Function: <code>aa_map_file_to_perms</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813848f9)
Location: security/apparmor/include/file.h:220
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_receive
```
```
In security/apparmor/file.c (ffffffff81388aef)
Location: security/apparmor/include/file.h:220
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813bf3e9)
Location: security/apparmor/include/file.h:221
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff813c3636)
Location: security/apparmor/include/file.h:221
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813d75f9)
Location: security/apparmor/include/file.h:221
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff813dabc6)
Location: security/apparmor/include/file.h:221
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813e8469)
Location: security/apparmor/include/file.h:220
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff813ebc26)
Location: security/apparmor/include/file.h:220
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8140f889)
Location: security/apparmor/include/file.h:217
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff81413566)
Location: security/apparmor/include/file.h:217
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81441de9)
Location: security/apparmor/include/file.h:217
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff814458d1)
Location: security/apparmor/include/file.h:217
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8145e7f9)
Location: security/apparmor/include/file.h:220
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff814627d5)
Location: security/apparmor/include/file.h:220
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148bcf9)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff8148fa95)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814a5bb9)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff814a9955)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81501968)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff815072a5)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8151eaff)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff81524355)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8152530a)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff8152a535)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8158359a)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff815888d5)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81623b9c)
Location: security/apparmor/include/file.h:144
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff81628f85)
Location: security/apparmor/include/file.h:144
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816d7fbc)
Location: security/apparmor/include/file.h:149
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff816dd825)
Location: security/apparmor/include/file.h:149
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8171142f)
Location: security/apparmor/include/file.h:149
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff81716e38)
Location: security/apparmor/include/file.h:149
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8174ea2f)
Location: security/apparmor/include/file.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff81755998)
Location: security/apparmor/include/file.h:112
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffff80001059c040)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffff8000105a0358)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c074d5a8)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (c0750fd4)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c000000000713f90)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (c00000000071a5e0)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffe0003e7cc4)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffe0003eb322)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149e199)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff814a1f35)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148ebb9)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff81492955)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149a239)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff8149dfd5)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814b2369)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff814b65c5)
Location: security/apparmor/include/file.h:216
Inline: True
Inline callers:
  - security/apparmor/file.c:match_file
```
</details>
</li>
</ul>

## Differences
