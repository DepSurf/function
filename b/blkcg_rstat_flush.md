# Function: <code>blkcg_rstat_flush</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blkcg_rstat_flush(struct cgroup_subsys_state *css, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8156a670)
Location: block/blk-cgroup.c:1149
Inline: False
```
**Symbols:**

```
ffffffff8156a670-ffffffff8156a868: blkcg_rstat_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blkcg_rstat_flush(struct cgroup_subsys_state *css, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815850d0)
Location: block/blk-cgroup.c:764
Inline: False
```
**Symbols:**

```
ffffffff815850d0-ffffffff815852bb: blkcg_rstat_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blkcg_rstat_flush(struct cgroup_subsys_state *css, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158bc60)
Location: block/blk-cgroup.c:762
Inline: False
```
**Symbols:**

```
ffffffff8158bc60-ffffffff8158be61: blkcg_rstat_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blkcg_rstat_flush(struct cgroup_subsys_state *css, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f1070)
Location: block/blk-cgroup.c:788
Inline: False
```
**Symbols:**

```
ffffffff815f1070-ffffffff815f153f: blkcg_rstat_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blkcg_rstat_flush(struct cgroup_subsys_state *css, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a28a0)
Location: block/blk-cgroup.c:849
Inline: True
```
**Symbols:**

```
ffffffff816a28a0-ffffffff816a2d82: blkcg_rstat_flush.part.0 (STB_LOCAL)
ffffffff816a2d90-ffffffff816a2dc2: blkcg_rstat_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blkcg_rstat_flush(struct cgroup_subsys_state *css, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81761cc0)
Location: block/blk-cgroup.c:861
Inline: False
```
**Symbols:**

```
ffffffff81761cc0-ffffffff81761e43: blkcg_rstat_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blkcg_rstat_flush(struct cgroup_subsys_state *css, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817a0780)
Location: block/blk-cgroup.c:1034
Inline: False
```
**Symbols:**

```
ffffffff817a0780-ffffffff817a07b9: blkcg_rstat_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blkcg_rstat_flush(struct cgroup_subsys_state *css, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e42b0)
Location: block/blk-cgroup.c:1047
Inline: False
```
**Symbols:**

```
ffffffff817e42b0-ffffffff817e42e9: blkcg_rstat_flush (STB_LOCAL)
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
