# Function: <code>__d_lookup_rcu_op_compare</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dentry *__d_lookup_rcu_op_compare(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2277
Inline: False
Direct callers:
  - fs/dcache.c:__d_lookup_rcu
```
**Symbols:**

```
ffffffff8149d750-ffffffff8149d841: __d_lookup_rcu_op_compare (STB_LOCAL)
ffffffff82068912-ffffffff82068937: __d_lookup_rcu_op_compare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dentry *__d_lookup_rcu_op_compare(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2277
Inline: False
Direct callers:
  - fs/dcache.c:__d_lookup_rcu
```
**Symbols:**

```
ffffffff814d2a70-ffffffff814d2b61: __d_lookup_rcu_op_compare (STB_LOCAL)
ffffffff820e8250-ffffffff820e8275: __d_lookup_rcu_op_compare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dentry *__d_lookup_rcu_op_compare(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2101
Inline: False
Direct callers:
  - fs/dcache.c:__d_lookup_rcu
```
**Symbols:**

```
ffffffff81505440-ffffffff81505531: __d_lookup_rcu_op_compare (STB_LOCAL)
ffffffff821c4f8d-ffffffff821c4fb2: __d_lookup_rcu_op_compare.cold (STB_LOCAL)
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
