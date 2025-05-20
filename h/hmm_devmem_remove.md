# Function: <code>hmm_devmem_remove</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hmm_devmem_remove(struct hmm_devmem *devmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff8126de87)
Location: mm/hmm.c:1154
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_add
Direct callers:
  - mm/hmm.c:hmm_devmem_add
```
**Symbols:**

```
ffffffff8126dbc0-ffffffff8126dc54: hmm_devmem_remove.part.16 (STB_LOCAL)
ffffffff8126dc60-ffffffff8126dc77: hmm_devmem_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hmm_devmem_remove(struct hmm_devmem *devmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff8129254d)
Location: mm/hmm.c:1319
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_add
Direct callers:
  - mm/hmm.c:hmm_devmem_add
```
**Symbols:**

```
ffffffff812922b0-ffffffff81292344: hmm_devmem_remove.part.26 (STB_LOCAL)
ffffffff81292350-ffffffff81292366: hmm_devmem_remove (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
