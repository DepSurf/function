# Function: <code>bitmap_wait_writes</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bitmap_wait_writes(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8172ee60)
Location: drivers/md/bitmap.c:427
Inline: True
Direct callers:
  - drivers/md/bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff8172ee60-ffffffff8172ef02: bitmap_wait_writes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bitmap_wait_writes(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81747fc0)
Location: drivers/md/bitmap.c:428
Inline: True
Direct callers:
  - drivers/md/bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff81747fc0-ffffffff81748062: bitmap_wait_writes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bitmap_wait_writes(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817ba250)
Location: drivers/md/md-bitmap.c:428
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff817ba250-ffffffff817ba2f2: bitmap_wait_writes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bitmap_wait_writes(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81802230)
Location: drivers/md/md-bitmap.c:428
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff81802230-ffffffff818022d2: bitmap_wait_writes (STB_LOCAL)
```
</details>
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
