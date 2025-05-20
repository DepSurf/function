# Function: <code>__d_lookup_unhash</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
wait_queue_head_t *__d_lookup_unhash(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149e420)
Location: fs/dcache.c:2746
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
```
**Symbols:**

```
ffffffff8149e420-ffffffff8149e517: __d_lookup_unhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
wait_queue_head_t *__d_lookup_unhash(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d3740)
Location: fs/dcache.c:2746
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
```
**Symbols:**

```
ffffffff814d3740-ffffffff814d3837: __d_lookup_unhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
wait_queue_head_t *__d_lookup_unhash(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81505ec0)
Location: fs/dcache.c:2570
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
```
**Symbols:**

```
ffffffff81505ec0-ffffffff81505fb7: __d_lookup_unhash (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
