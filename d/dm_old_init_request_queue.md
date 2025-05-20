# Function: <code>dm_old_init_request_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dm_old_init_request_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8170fd60)
Location: drivers/md/dm-rq.c:812
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff8170fd60-ffffffff8170fe45: dm_old_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dm_old_init_request_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81741d40)
Location: drivers/md/dm-rq.c:827
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81741d40-ffffffff81741e29: dm_old_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dm_old_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8175b7a0)
Location: drivers/md/dm-rq.c:684
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff8175b7a0-ffffffff8175b8e6: dm_old_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dm_old_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff817cda00)
Location: drivers/md/dm-rq.c:681
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff817cda00-ffffffff817cdb2e: dm_old_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dm_old_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818167e0)
Location: drivers/md/dm-rq.c:698
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff818167e0-ffffffff81816915: dm_old_init_request_queue (STB_GLOBAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dm_table *t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
