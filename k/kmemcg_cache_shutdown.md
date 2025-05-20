# Function: <code>kmemcg_cache_shutdown</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kmemcg_cache_shutdown(struct percpu_ref *percpu_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81240420)
Location: mm/slab_common.c:744
Inline: False
```
**Symbols:**

```
ffffffff81240420-ffffffff8124049e: kmemcg_cache_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kmemcg_cache_shutdown(struct percpu_ref *percpu_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124e830)
Location: mm/slab_common.c:745
Inline: False
```
**Symbols:**

```
ffffffff8124e830-ffffffff8124e8ae: kmemcg_cache_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kmemcg_cache_shutdown(struct percpu_ref *percpu_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127cc50)
Location: mm/slab_common.c:745
Inline: False
```
**Symbols:**

```
ffffffff8127cc50-ffffffff8127ccce: kmemcg_cache_shutdown (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void kmemcg_cache_shutdown(struct percpu_ref *percpu_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e56f0)
Location: mm/slab_common.c:745
Inline: False
```
**Symbols:**

```
ffff8000102e56f0-ffff8000102e57e4: kmemcg_cache_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kmemcg_cache_shutdown(struct percpu_ref *percpu_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0509818)
Location: mm/slab_common.c:745
Inline: False
```
**Symbols:**

```
c0509818-c05098a4: kmemcg_cache_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kmemcg_cache_shutdown(struct percpu_ref *percpu_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a6490)
Location: mm/slab_common.c:745
Inline: False
```
**Symbols:**

```
c0000000003a6490-c0000000003a6564: kmemcg_cache_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kmemcg_cache_shutdown(struct percpu_ref *percpu_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fb714)
Location: mm/slab_common.c:745
Inline: False
```
**Symbols:**

```
ffffffe0001fb714-ffffffe0001fb7a0: kmemcg_cache_shutdown (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void kmemcg_cache_shutdown(struct percpu_ref *percpu_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81246e80)
Location: mm/slab_common.c:745
Inline: False
```
**Symbols:**

```
ffffffff81246e80-ffffffff81246efe: kmemcg_cache_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kmemcg_cache_shutdown(struct percpu_ref *percpu_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81239e30)
Location: mm/slab_common.c:745
Inline: False
```
**Symbols:**

```
ffffffff81239e30-ffffffff81239eae: kmemcg_cache_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kmemcg_cache_shutdown(struct percpu_ref *percpu_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81244c20)
Location: mm/slab_common.c:745
Inline: False
```
**Symbols:**

```
ffffffff81244c20-ffffffff81244c9e: kmemcg_cache_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kmemcg_cache_shutdown(struct percpu_ref *percpu_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812543e0)
Location: mm/slab_common.c:745
Inline: False
```
**Symbols:**

```
ffffffff812543e0-ffffffff8125445e: kmemcg_cache_shutdown (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
