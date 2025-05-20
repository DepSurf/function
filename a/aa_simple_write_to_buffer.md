# Function: <code>aa_simple_write_to_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
char *aa_simple_write_to_buffer(const char *userbuf, size_t alloc_size, size_t copy_size, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813750b0)
Location: security/apparmor/apparmorfs.c:88
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff813750b0-ffffffff8137512c: aa_simple_write_to_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct aa_loaddata *aa_simple_write_to_buffer(const char *userbuf, size_t alloc_size, size_t copy_size, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813ab590)
Location: security/apparmor/apparmorfs.c:91
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff813ab590-ffffffff813ab641: aa_simple_write_to_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct aa_loaddata *aa_simple_write_to_buffer(const char *userbuf, size_t alloc_size, size_t copy_size, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813c2360)
Location: security/apparmor/apparmorfs.c:91
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff813c2360-ffffffff813c2411: aa_simple_write_to_buffer (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff813dad48)
Location: security/apparmor/apparmorfs.c:382
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff813d9370-ffffffff813d93df: aa_simple_write_to_buffer.isra.24.part.25 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff8140122d)
Location: security/apparmor/apparmorfs.c:383
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff813ff4b0-ffffffff813ff51f: aa_simple_write_to_buffer.isra.26.part.27 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff81431e61)
Location: security/apparmor/apparmorfs.c:380
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff81430430-ffffffff814304ab: aa_simple_write_to_buffer.isra.31.part.32 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff8144ee12)
Location: security/apparmor/apparmorfs.c:381
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8144cf80-ffffffff8144cffb: aa_simple_write_to_buffer.isra.31.part.32 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff8147c9bc)
Location: security/apparmor/apparmorfs.c:386
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8147ad20-ffffffff8147ad9e: aa_simple_write_to_buffer.isra.0.part.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff8149668c)
Location: security/apparmor/apparmorfs.c:354
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff814947a0-ffffffff81494829: aa_simple_write_to_buffer.isra.0.part.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff814ee10c)
Location: security/apparmor/apparmorfs.c:384
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff814ec050-ffffffff814ec0d9: aa_simple_write_to_buffer.part.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff8150b79c)
Location: security/apparmor/apparmorfs.c:384
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff81509430-ffffffff815094b9: aa_simple_write_to_buffer.part.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff81512128)
Location: security/apparmor/apparmorfs.c:384
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8150fe60-ffffffff8150fee9: aa_simple_write_to_buffer.part.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff8156fd28)
Location: security/apparmor/apparmorfs.c:384
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8156d6b0-ffffffff8156d739: aa_simple_write_to_buffer.part.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff8160b210)
Location: security/apparmor/apparmorfs.c:387
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8160b210-ffffffff8160b2d1: aa_simple_write_to_buffer.isra.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff816bd400)
Location: security/apparmor/apparmorfs.c:388
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff816bd400-ffffffff816bd4c1: aa_simple_write_to_buffer.isra.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff816f5ec0)
Location: security/apparmor/apparmorfs.c:389
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff816f5ec0-ffffffff816f5f81: aa_simple_write_to_buffer.isra.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff81732c20)
Location: security/apparmor/apparmorfs.c:389
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff81732c20-ffffffff81732ce1: aa_simple_write_to_buffer.isra.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffff80001058c6a8)
Location: security/apparmor/apparmorfs.c:354
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffff80001058b6a8-ffff80001058b750: aa_simple_write_to_buffer.isra.0.part.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (c073d244)
Location: security/apparmor/apparmorfs.c:354
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
c073ba78-c073bb8c: aa_simple_write_to_buffer.part.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (c0000000006fe390)
Location: security/apparmor/apparmorfs.c:354
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
c0000000006fbba0-c0000000006fbc94: aa_simple_write_to_buffer.isra.0.part.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffe0003daad2)
Location: security/apparmor/apparmorfs.c:354
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffe0003d9cd6-ffffffe0003d9d5c: aa_simple_write_to_buffer.isra.0.part.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff8148ec6c)
Location: security/apparmor/apparmorfs.c:354
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8148cd80-ffffffff8148ce09: aa_simple_write_to_buffer.isra.0.part.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff8147f68c)
Location: security/apparmor/apparmorfs.c:354
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8147d7a0-ffffffff8147d829: aa_simple_write_to_buffer.isra.0.part.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff8148ad0c)
Location: security/apparmor/apparmorfs.c:354
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff81488e20-ffffffff81488ea9: aa_simple_write_to_buffer.isra.0.part.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff814a2a27)
Location: security/apparmor/apparmorfs.c:354
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff814a0960-ffffffff814a09e9: aa_simple_write_to_buffer.isra.0.part.0 (STB_LOCAL)
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
<b>Return type changed. </b>
<code>char *</code> ➡️ <code>struct aa_loaddata *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
