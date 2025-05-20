# Function: <code>bpf_free_kfunc_btf_tab</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_free_kfunc_btf_tab(struct bpf_kfunc_btf_tab *tab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81290000)
Location: kernel/bpf/verifier.c:1956
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
```
**Symbols:**

```
ffffffff81290000-ffffffff812900a6: bpf_free_kfunc_btf_tab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_free_kfunc_btf_tab(struct bpf_kfunc_btf_tab *tab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812e8f50)
Location: kernel/bpf/verifier.c:2171
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
```
**Symbols:**

```
ffffffff812e8f50-ffffffff812e8ff6: bpf_free_kfunc_btf_tab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_free_kfunc_btf_tab(struct bpf_kfunc_btf_tab *tab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff813151c0)
Location: kernel/bpf/verifier.c:2589
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
```
**Symbols:**

```
ffffffff813151c0-ffffffff81315266: bpf_free_kfunc_btf_tab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_free_kfunc_btf_tab(struct bpf_kfunc_btf_tab *tab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8133ced0)
Location: kernel/bpf/verifier.c:2662
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
```
**Symbols:**

```
ffffffff8133ced0-ffffffff8133cf76: bpf_free_kfunc_btf_tab (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
