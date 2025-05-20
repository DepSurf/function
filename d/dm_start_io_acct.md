# Function: <code>dm_start_io_acct</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void dm_start_io_acct(struct dm_io *io, struct bio *clone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b6ffe0)
Location: drivers/md/dm.c:543
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
**Symbols:**

```
ffffffff81b6ffe0-ffffffff81b7006f: dm_start_io_acct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dm_start_io_acct(struct dm_io *io, struct bio *clone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0c700)
Location: drivers/md/dm.c:538
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
**Symbols:**

```
ffffffff81d0c700-ffffffff81d0c78f: dm_start_io_acct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dm_start_io_acct(struct dm_io *io, struct bio *clone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d76a90)
Location: drivers/md/dm.c:542
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
**Symbols:**

```
ffffffff81d76a90-ffffffff81d76b2a: dm_start_io_acct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_start_io_acct(struct dm_io *io, struct bio *clone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2dcc0)
Location: drivers/md/dm.c:542
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
**Symbols:**

```
ffffffff81e2dcc0-ffffffff81e2dd5a: dm_start_io_acct (STB_LOCAL)
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
