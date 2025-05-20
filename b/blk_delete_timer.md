# Function: <code>blk_delete_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_delete_timer(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-timeout.c (ffffffff813c1f70)
Location: block/blk-timeout.c:78
Inline: True
Direct callers:
  - block/blk-core.c:blk_finish_request
```
**Symbols:**

```
ffffffff813c1f70-ffffffff813c1fa5: blk_delete_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_delete_timer(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-timeout.c (ffffffff81405f00)
Location: block/blk-timeout.c:78
Inline: True
Direct callers:
  - block/blk-core.c:blk_finish_request
```
**Symbols:**

```
ffffffff81405f00-ffffffff81405f35: blk_delete_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_delete_timer(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-timeout.c (ffffffff81420190)
Location: block/blk-timeout.c:78
Inline: True
Direct callers:
  - block/blk-core.c:blk_finish_request
```
**Symbols:**

```
ffffffff81420190-ffffffff814201c5: blk_delete_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_delete_timer(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-timeout.c (ffffffff8142e150)
Location: block/blk-timeout.c:78
Inline: True
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_requeue_request
```
**Symbols:**

```
ffffffff8142e150-ffffffff8142e185: blk_delete_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_delete_timer(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-timeout.c (ffffffff81459380)
Location: block/blk-timeout.c:78
Inline: True
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_requeue_request
```
**Symbols:**

```
ffffffff81459380-ffffffff814593b5: blk_delete_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_delete_timer(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-timeout.c (ffffffff8148c8d0)
Location: block/blk-timeout.c:76
Inline: True
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_requeue_request
```
**Symbols:**

```
ffffffff8148c8d0-ffffffff8148c905: blk_delete_timer (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
