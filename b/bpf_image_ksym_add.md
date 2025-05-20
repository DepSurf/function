# Function: <code>bpf_image_ksym_add</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_image_ksym_add(void *data, struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8121f011)
Location: kernel/bpf/trampoline.c:42
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff8121ede0-ffffffff8121ee21: bpf_image_ksym_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_image_ksym_add(void *data, struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812227da)
Location: kernel/bpf/trampoline.c:44
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_tramp_image_alloc
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff81222890-ffffffff812228d1: bpf_image_ksym_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_image_ksym_add(void *data, struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812276d4)
Location: kernel/bpf/trampoline.c:45
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff81226f00-ffffffff81226f41: bpf_image_ksym_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_image_ksym_add(void *data, struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8125f859)
Location: kernel/bpf/trampoline.c:45
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff8125f000-ffffffff8125f041: bpf_image_ksym_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_image_ksym_add(void *data, struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812a9f86)
Location: kernel/bpf/trampoline.c:57
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff812a9630-ffffffff812a9680: bpf_image_ksym_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_image_ksym_add(void *data, struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff813090dc)
Location: kernel/bpf/trampoline.c:119
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff81308870-ffffffff813088c0: bpf_image_ksym_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_image_ksym_add(void *data, struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81338054)
Location: kernel/bpf/trampoline.c:118
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff81337790-ffffffff813377e0: bpf_image_ksym_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_image_ksym_add(void *data, unsigned int size, struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8135df60)
Location: kernel/bpf/trampoline.c:118
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff8135d5d0-ffffffff8135d61e: bpf_image_ksym_add (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int size</code>
</li>
<li>
<b>Param reordered. </b>
<code>data, ksym</code> ➡️ <code>data, size, ksym</code>
</li>
</ul>
</details>
</li>
</ul>
