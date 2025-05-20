# Function: <code>__bpf_free_used_maps</code>

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
void __bpf_free_used_maps(struct bpf_prog_aux *aux, struct bpf_map **used_maps, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fae40)
Location: kernel/bpf/core.c:2056
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811fae40-ffffffff811faec5: __bpf_free_used_maps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_free_used_maps(struct bpf_prog_aux *aux, struct bpf_map **used_maps, u32 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9819)
Location: kernel/bpf/core.c:2102
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811fa130-ffffffff811fa18b: __bpf_free_used_maps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_free_used_maps(struct bpf_prog_aux *aux, struct bpf_map **used_maps, u32 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa6c9)
Location: kernel/bpf/core.c:2198
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811fb090-ffffffff811fb0eb: __bpf_free_used_maps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_free_used_maps(struct bpf_prog_aux *aux, struct bpf_map **used_maps, u32 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122bdd9)
Location: kernel/bpf/core.c:2218
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8122c7b0-ffffffff8122c80b: __bpf_free_used_maps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_free_used_maps(struct bpf_prog_aux *aux, struct bpf_map **used_maps, u32 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126d958)
Location: kernel/bpf/core.c:2504
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8126e480-ffffffff8126e4f1: __bpf_free_used_maps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_free_used_maps(struct bpf_prog_aux *aux, struct bpf_map **used_maps, u32 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c2d97)
Location: kernel/bpf/core.c:2498
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff812c3af0-ffffffff812c3b61: __bpf_free_used_maps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_free_used_maps(struct bpf_prog_aux *aux, struct bpf_map **used_maps, u32 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e9c8a)
Location: kernel/bpf/core.c:2515
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff812ea940-ffffffff812ea9b1: __bpf_free_used_maps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __bpf_free_used_maps(struct bpf_prog_aux *aux, struct bpf_map **used_maps, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:2691
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff821ba567-ffffffff821ba582: __bpf_free_used_maps.cold (STB_LOCAL)
ffffffff81308c50-ffffffff81308ce3: __bpf_free_used_maps (STB_GLOBAL)
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
