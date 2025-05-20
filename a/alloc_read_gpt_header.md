# Function: <code>alloc_read_gpt_header</code>

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
In block/partitions/efi.c (ffffffff813d3b91)
Location: block/partitions/efi.c:322
Inline: True
Inline callers:
  - block/partitions/efi.c:is_gpt_valid
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
In block/partitions/efi.c (ffffffff814196ea)
Location: block/partitions/efi.c:322
Inline: True
Inline callers:
  - block/partitions/efi.c:is_gpt_valid
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
In block/partitions/efi.c (ffffffff81434c1a)
Location: block/partitions/efi.c:322
Inline: True
Inline callers:
  - block/partitions/efi.c:is_gpt_valid
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
In block/partitions/efi.c (ffffffff814419df)
Location: block/partitions/efi.c:322
Inline: True
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
In block/partitions/efi.c (ffffffff8146e34f)
Location: block/partitions/efi.c:322
Inline: True
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
In block/partitions/efi.c (ffffffff814a2005)
Location: block/partitions/efi.c:322
Inline: True
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
In block/partitions/efi.c (ffffffff814bc515)
Location: block/partitions/efi.c:322
Inline: True
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
In block/partitions/efi.c (ffffffff814eab95)
Location: block/partitions/efi.c:308
Inline: True
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
In block/partitions/efi.c (ffffffff81503f55)
Location: block/partitions/efi.c:308
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
gpt_header *alloc_read_gpt_header(struct parsed_partitions *state, u64 lba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff81564840)
Location: block/partitions/efi.c:308
Inline: False
```
**Symbols:**

```
ffffffff81564840-ffffffff815648c1: alloc_read_gpt_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
gpt_header *alloc_read_gpt_header(struct parsed_partitions *state, u64 lba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff8157f950)
Location: block/partitions/efi.c:308
Inline: False
```
**Symbols:**

```
ffffffff8157f950-ffffffff8157f9ce: alloc_read_gpt_header (STB_LOCAL)
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
In block/partitions/efi.c (ffffffff815874a6)
Location: block/partitions/efi.c:308
Inline: True
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
In block/partitions/efi.c (ffffffff815ed006)
Location: block/partitions/efi.c:306
Inline: True
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
In block/partitions/efi.c (ffffffff8169d586)
Location: block/partitions/efi.c:306
Inline: True
Inline callers:
  - block/partitions/efi.c:is_gpt_valid
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
In block/partitions/efi.c (ffffffff8175bfc6)
Location: block/partitions/efi.c:306
Inline: True
Inline callers:
  - block/partitions/efi.c:is_gpt_valid
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
In block/partitions/efi.c (ffffffff8179a836)
Location: block/partitions/efi.c:306
Inline: True
Inline callers:
  - block/partitions/efi.c:is_gpt_valid
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
In block/partitions/efi.c (ffffffff817de266)
Location: block/partitions/efi.c:306
Inline: True
Inline callers:
  - block/partitions/efi.c:is_gpt_valid
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
In block/partitions/efi.c (ffff8000106060ec)
Location: block/partitions/efi.c:308
Inline: True
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
In block/partitions/efi.c (c07b134c)
Location: block/partitions/efi.c:308
Inline: True
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
In block/partitions/efi.c (c0000000007a2014)
Location: block/partitions/efi.c:308
Inline: True
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
In block/partitions/efi.c (ffffffe000440fb8)
Location: block/partitions/efi.c:308
Inline: True
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
In block/partitions/efi.c (ffffffff814fc535)
Location: block/partitions/efi.c:308
Inline: True
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
In block/partitions/efi.c (ffffffff814eca45)
Location: block/partitions/efi.c:308
Inline: True
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
In block/partitions/efi.c (ffffffff814f85c5)
Location: block/partitions/efi.c:308
Inline: True
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
In block/partitions/efi.c (ffffffff81511625)
Location: block/partitions/efi.c:308
Inline: True
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
