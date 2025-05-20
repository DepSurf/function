# Function: <code>unpack_table</code>

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
In security/apparmor/match.c (ffffffff813790db)
Location: security/apparmor/match.c:64
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff813b1ec4)
Location: security/apparmor/match.c:64
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff813c9084)
Location: security/apparmor/match.c:64
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff813de738)
Location: security/apparmor/match.c:64
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff814050c8)
Location: security/apparmor/match.c:64
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff814361bd)
Location: security/apparmor/match.c:81
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff81452ddd)
Location: security/apparmor/match.c:81
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff8148078c)
Location: security/apparmor/match.c:77
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff8149a48c)
Location: security/apparmor/match.c:77
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct table_header *unpack_table(char *blob, size_t bsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814f2aa0)
Location: security/apparmor/match.c:77
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff814f2aa0-ffffffff814f2be5: unpack_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct table_header *unpack_table(char *blob, size_t bsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8150fc70)
Location: security/apparmor/match.c:77
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff8150fc70-ffffffff8150fdb5: unpack_table (STB_LOCAL)
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
In security/apparmor/match.c (ffffffff815169a7)
Location: security/apparmor/match.c:77
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff815749a7)
Location: security/apparmor/match.c:77
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct table_header *unpack_table(char *blob, size_t bsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81611f50)
Location: security/apparmor/match.c:77
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff81611f50-ffffffff816120eb: unpack_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct table_header *unpack_table(char *blob, size_t bsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816c4c70)
Location: security/apparmor/match.c:77
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff816c4c70-ffffffff816c4e0b: unpack_table (STB_LOCAL)
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
In security/apparmor/match.c (ffffffff816fdba6)
Location: security/apparmor/match.c:33
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff8173b137)
Location: security/apparmor/match.c:33
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffff800010590534)
Location: security/apparmor/match.c:77
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (c0741278)
Location: security/apparmor/match.c:77
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (c000000000703bfc)
Location: security/apparmor/match.c:77
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffe0003de012)
Location: security/apparmor/match.c:77
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff81492a6c)
Location: security/apparmor/match.c:77
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff8148348c)
Location: security/apparmor/match.c:77
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff8148eb0c)
Location: security/apparmor/match.c:77
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
In security/apparmor/match.c (ffffffff814a6a1c)
Location: security/apparmor/match.c:77
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
