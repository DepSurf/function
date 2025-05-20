# Function: <code>__part_end_io_acct</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __part_end_io_acct(struct block_device *part, unsigned int op, long unsigned int start_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f530)
Location: block/blk-core.c:1355
Inline: False
Direct callers:
  - block/blk-core.c:disk_end_io_acct
  - block/blk-core.c:part_end_io_acct
```
**Symbols:**

```
ffffffff8155f530-ffffffff8155f5ea: __part_end_io_acct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __part_end_io_acct(struct block_device *part, unsigned int op, long unsigned int start_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81567cc0)
Location: block/blk-core.c:1347
Inline: False
Direct callers:
  - block/blk-core.c:disk_end_io_acct
  - block/blk-core.c:bio_end_io_acct_remapped
```
**Symbols:**

```
ffffffff81567cc0-ffffffff81567d79: __part_end_io_acct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __part_end_io_acct(struct block_device *part, unsigned int op, long unsigned int start_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cc2f0)
Location: block/blk-core.c:1337
Inline: False
Direct callers:
  - block/blk-core.c:disk_end_io_acct
  - block/blk-core.c:bio_end_io_acct_remapped
```
**Symbols:**

```
ffffffff815cc2f0-ffffffff815cc3c2: __part_end_io_acct (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
