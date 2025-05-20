# Function: <code>dec_elem_count</code>

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
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dec_elem_count(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812f886d)
Location: kernel/bpf/hashtab.c:894
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff812f8830-ffffffff812f8894: dec_elem_count (STB_LOCAL)
ffffffff8206157e-ffffffff82061593: dec_elem_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dec_elem_count(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8132696d)
Location: kernel/bpf/hashtab.c:909
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff81326930-ffffffff81326994: dec_elem_count (STB_LOCAL)
ffffffff820e0b0b-ffffffff820e0b20: dec_elem_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dec_elem_count(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134afba)
Location: kernel/bpf/hashtab.c:923
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff8134af70-ffffffff8134afe3: dec_elem_count (STB_LOCAL)
ffffffff821bd2cb-ffffffff821bd2e0: dec_elem_count.cold (STB_LOCAL)
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
