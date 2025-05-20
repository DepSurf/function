# Function: <code>fsync_buffers_list</code>

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
In fs/buffer.c (ffffffff81246555)
Location: fs/buffer.c:731
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff8126f497)
Location: fs/buffer.c:724
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff81282697)
Location: fs/buffer.c:725
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff8128fd51)
Location: fs/buffer.c:722
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff812b2a81)
Location: fs/buffer.c:701
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff812da99f)
Location: fs/buffer.c:671
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff812efe7f)
Location: fs/buffer.c:672
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff8131170c)
Location: fs/buffer.c:673
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff813246ec)
Location: fs/buffer.c:673
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fsync_buffers_list(spinlock_t *lock, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135b100)
Location: fs/buffer.c:699
Inline: False
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffffffff8135b100-ffffffff8135b35d: fsync_buffers_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fsync_buffers_list(spinlock_t *lock, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81369220)
Location: fs/buffer.c:698
Inline: False
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffffffff81369220-ffffffff8136947d: fsync_buffers_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fsync_buffers_list(spinlock_t *lock, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81371540)
Location: fs/buffer.c:698
Inline: False
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffffffff81371540-ffffffff81371860: fsync_buffers_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fsync_buffers_list(spinlock_t *lock, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813bff80)
Location: fs/buffer.c:673
Inline: False
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffffffff813bff80-ffffffff813c02fe: fsync_buffers_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fsync_buffers_list(spinlock_t *lock, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81444c10)
Location: fs/buffer.c:670
Inline: False
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffffffff81444c10-ffffffff81444fa5: fsync_buffers_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fsync_buffers_list(spinlock_t *lock, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d3a40)
Location: fs/buffer.c:670
Inline: False
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffffffff814d3a40-ffffffff814d3df9: fsync_buffers_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fsync_buffers_list(spinlock_t *lock, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150ba50)
Location: fs/buffer.c:781
Inline: False
Direct callers:
  - fs/buffer.c:generic_buffers_fsync_noflush
```
**Symbols:**

```
ffffffff8150ba50-ffffffff8150be09: fsync_buffers_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fsync_buffers_list(spinlock_t *lock, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81540650)
Location: fs/buffer.c:769
Inline: False
Direct callers:
  - fs/buffer.c:generic_buffers_fsync_noflush
```
**Symbols:**

```
ffffffff81540650-ffffffff81540a09: fsync_buffers_list (STB_LOCAL)
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
In fs/buffer.c (ffff8000103ddb14)
Location: fs/buffer.c:673
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fsync_buffers_list(spinlock_t *lock, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b6f94)
Location: fs/buffer.c:673
Inline: False
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
c05b6f94-c05b72f8: fsync_buffers_list (STB_LOCAL)
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
In fs/buffer.c (c0000000004e3658)
Location: fs/buffer.c:673
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffe000295a26)
Location: fs/buffer.c:673
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff8131cccc)
Location: fs/buffer.c:673
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff8130d86c)
Location: fs/buffer.c:673
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff8131a79c)
Location: fs/buffer.c:673
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff8132c497)
Location: fs/buffer.c:673
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
