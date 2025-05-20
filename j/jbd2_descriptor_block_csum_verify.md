# Function: <code>jbd2_descriptor_block_csum_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81319521)
Location: fs/jbd2/recovery.c:177
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81319220-ffffffff813192b9: jbd2_descriptor_block_csum_verify.part.9 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff8132f511)
Location: fs/jbd2/recovery.c:177
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff8132f210-ffffffff8132f2a9: jbd2_descriptor_block_csum_verify.part.9 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813445bd)
Location: fs/jbd2/recovery.c:177
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813442d0-ffffffff81344369: jbd2_descriptor_block_csum_verify.part.9 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff81368c5d)
Location: fs/jbd2/recovery.c:177
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81368970-ffffffff81368a09: jbd2_descriptor_block_csum_verify.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int jbd2_descriptor_block_csum_verify(journal_t *j, void *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81397170)
Location: fs/jbd2/recovery.c:174
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81397170-ffffffff81397244: jbd2_descriptor_block_csum_verify (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813b05fb)
Location: fs/jbd2/recovery.c:174
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813afee0-ffffffff813aff79: jbd2_descriptor_block_csum_verify.part.11 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813da753)
Location: fs/jbd2/recovery.c:174
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813da470-ffffffff813da502: jbd2_descriptor_block_csum_verify.part.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813f47a3)
Location: fs/jbd2/recovery.c:174
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813f44c0-ffffffff813f4552: jbd2_descriptor_block_csum_verify.part.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff81441a09)
Location: fs/jbd2/recovery.c:174
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:scan_revoke_records
  - fs/jbd2/recovery.c:scan_revoke_records
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int jbd2_descriptor_block_csum_verify(journal_t *j, void *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff8145dbd0)
Location: fs/jbd2/recovery.c:173
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff8145dbd0-ffffffff8145dc9d: jbd2_descriptor_block_csum_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int jbd2_descriptor_block_csum_verify(journal_t *j, void *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff814633d0)
Location: fs/jbd2/recovery.c:173
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff814633d0-ffffffff81463497: jbd2_descriptor_block_csum_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int jbd2_descriptor_block_csum_verify(journal_t *j, void *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff814b8870)
Location: fs/jbd2/recovery.c:173
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff814b8870-ffffffff814b8937: jbd2_descriptor_block_csum_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int jbd2_descriptor_block_csum_verify(journal_t *j, void *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff815423c0)
Location: fs/jbd2/recovery.c:173
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff815423c0-ffffffff815424b2: jbd2_descriptor_block_csum_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int jbd2_descriptor_block_csum_verify(journal_t *j, void *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff815e10d0)
Location: fs/jbd2/recovery.c:178
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff815e10d0-ffffffff815e11c2: jbd2_descriptor_block_csum_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int jbd2_descriptor_block_csum_verify(journal_t *j, void *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff816189c0)
Location: fs/jbd2/recovery.c:179
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff816189c0-ffffffff81618ab2: jbd2_descriptor_block_csum_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int jbd2_descriptor_block_csum_verify(journal_t *j, void *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81651940)
Location: fs/jbd2/recovery.c:179
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff81651940-ffffffff81651a32: jbd2_descriptor_block_csum_verify (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffff8000104d010c)
Location: fs/jbd2/recovery.c:174
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffff8000104cfe50-ffff8000104cfeb4: jbd2_descriptor_block_csum_verify.part.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (c0692e00)
Location: fs/jbd2/recovery.c:174
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
c0692928-c069297c: jbd2_descriptor_block_csum_verify.part.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (c0000000006091b0)
Location: fs/jbd2/recovery.c:174
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
c000000000608d50-c000000000608e28: jbd2_descriptor_block_csum_verify.part.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffe000347954)
Location: fs/jbd2/recovery.c:174
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffe000347424-ffffffe0003474c8: jbd2_descriptor_block_csum_verify.part.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813ecd83)
Location: fs/jbd2/recovery.c:174
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813ecaa0-ffffffff813ecb32: jbd2_descriptor_block_csum_verify.part.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813dd803)
Location: fs/jbd2/recovery.c:174
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813dd520-ffffffff813dd5b2: jbd2_descriptor_block_csum_verify.part.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813ea103)
Location: fs/jbd2/recovery.c:174
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813e9e20-ffffffff813e9eb2: jbd2_descriptor_block_csum_verify.part.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff813ffa52)
Location: fs/jbd2/recovery.c:174
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff813ff760-ffffffff813ff7f2: jbd2_descriptor_block_csum_verify.part.0 (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
