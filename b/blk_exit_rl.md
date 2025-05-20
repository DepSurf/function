# Function: <code>blk_exit_rl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_exit_rl(struct request_list *rl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b9990)
Location: block/blk-core.c:637
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-cgroup.c:blkg_free
```
**Symbols:**

```
ffffffff813b9990-ffffffff813b99aa: blk_exit_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_exit_rl(struct request_list *rl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fd780)
Location: block/blk-core.c:639
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-cgroup.c:blkg_free
```
**Symbols:**

```
ffffffff813fd780-ffffffff813fd79a: blk_exit_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_exit_rl(struct request_list *rl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814170e0)
Location: block/blk-core.c:640
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-cgroup.c:blkg_free
```
**Symbols:**

```
ffffffff814170e0-ffffffff814170fa: blk_exit_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_exit_rl(struct request_queue *q, struct request_list *rl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81424de0)
Location: block/blk-core.c:748
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81424de0-ffffffff81424e21: blk_exit_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_exit_rl(struct request_queue *q, struct request_list *rl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144fc60)
Location: block/blk-core.c:798
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff8144fc60-ffffffff8144fca1: blk_exit_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_exit_rl(struct request_queue *q, struct request_list *rl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81482e90)
Location: block/blk-core.c:898
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81482e90-ffffffff81482ed0: blk_exit_rl (STB_GLOBAL)
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>rl</code> ➡️ <code>q, rl</code>
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
