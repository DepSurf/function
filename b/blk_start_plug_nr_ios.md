# Function: <code>blk_start_plug_nr_ios</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_start_plug_nr_ios(struct blk_plug *plug, short unsigned int nr_ios);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff816784a5)
Location: block/blk-core.c:1104
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_plug
Direct callers:
  - io_uring/io_uring.c:io_init_req
```
**Symbols:**

```
ffffffff81679d00-ffffffff81679d74: blk_start_plug_nr_ios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_start_plug_nr_ios(struct blk_plug *plug, short unsigned int nr_ios);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81734995)
Location: block/blk-core.c:1042
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_plug
Direct callers:
  - io_uring/io_uring.c:io_init_req
```
**Symbols:**

```
ffffffff81736180-ffffffff817361f4: blk_start_plug_nr_ios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_start_plug_nr_ios(struct blk_plug *plug, short unsigned int nr_ios);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176e2c5)
Location: block/blk-core.c:1041
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_plug
Direct callers:
  - io_uring/io_uring.c:io_init_req
```
**Symbols:**

```
ffffffff817727f0-ffffffff81772860: blk_start_plug_nr_ios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_start_plug_nr_ios(struct blk_plug *plug, short unsigned int nr_ios);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b04e5)
Location: block/blk-core.c:1076
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_plug
Direct callers:
  - io_uring/io_uring.c:io_init_req
```
**Symbols:**

```
ffffffff817b4b90-ffffffff817b4c00: blk_start_plug_nr_ios (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
