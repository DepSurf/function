# Function: <code>dm_init_md_queue</code>

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
In drivers/md/dm.c (ffffffff816a3475)
Location: drivers/md/dm.c:2220
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_setup_md_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void dm_init_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81703d1b)
Location: drivers/md/dm.c:1382
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_init_normal_md_queue
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81703a80-ffffffff81703ab6: dm_init_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dm_init_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81735be0)
Location: drivers/md/dm.c:1437
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_init_normal_md_queue
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81735940-ffffffff81735976: dm_init_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dm_init_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174f44d)
Location: drivers/md/dm.c:1631
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_create
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff8174ed80-ffffffff8174edba: dm_init_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dm_init_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817c1699)
Location: drivers/md/dm.c:1622
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_create
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff817c0fd0-ffffffff817c0ff5: dm_init_md_queue (STB_GLOBAL)
```
</details>
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
