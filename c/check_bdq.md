# Function: <code>check_bdq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_bdq(struct dquot *dquot, qsize_t space, int prealloc, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81271040)
Location: fs/quota/dquot.c:1307
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_transfer
```
**Symbols:**

```
ffffffff81271040-ffffffff812711ee: check_bdq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_bdq(struct dquot *dquot, qsize_t space, int prealloc, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8129d530)
Location: fs/quota/dquot.c:1316
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff8129d530-ffffffff8129d6d2: check_bdq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_bdq(struct dquot *dquot, qsize_t space, int prealloc, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812b2e70)
Location: fs/quota/dquot.c:1313
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff812b2e70-ffffffff812b3012: check_bdq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_bdq(struct dquot *dquot, qsize_t space, int prealloc, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812c04c0)
Location: fs/quota/dquot.c:1319
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff812c04c0-ffffffff812c064c: check_bdq (STB_LOCAL)
```
</details>
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
</ul>
