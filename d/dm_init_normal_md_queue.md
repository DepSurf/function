# Function: <code>dm_init_normal_md_queue</code>

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
void dm_init_normal_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81703ac0)
Location: drivers/md/dm.c:1403
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff81703ac0-ffffffff81703b22: dm_init_normal_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dm_init_normal_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81735980)
Location: drivers/md/dm.c:1458
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff81735980-ffffffff817359e2: dm_init_normal_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dm_init_normal_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174f446)
Location: drivers/md/dm.c:1652
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
Direct callers:
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff8174edc0-ffffffff8174ee17: dm_init_normal_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dm_init_normal_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817c1699)
Location: drivers/md/dm.c:1632
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
Direct callers:
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff817c1000-ffffffff817c103f: dm_init_normal_md_queue (STB_GLOBAL)
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
In drivers/md/dm.c (ffffffff81809d43)
Location: drivers/md/dm.c:1794
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_setup_md_queue
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
In drivers/md/dm.c (ffffffff81835e10)
Location: drivers/md/dm.c:1846
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
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
In drivers/md/dm.c (ffffffff81878944)
Location: drivers/md/dm.c:1878
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
</details>
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
