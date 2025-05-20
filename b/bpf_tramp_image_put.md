# Function: <code>bpf_tramp_image_put</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_tramp_image_put(struct bpf_tramp_image *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81222380)
Location: kernel/bpf/trampoline.c:213
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff81222380-ffffffff812223e1: bpf_tramp_image_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_tramp_image_put(struct bpf_tramp_image *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81226d10)
Location: kernel/bpf/trampoline.c:243
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff81226d10-ffffffff81226d71: bpf_tramp_image_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_tramp_image_put(struct bpf_tramp_image *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8125ee10)
Location: kernel/bpf/trampoline.c:245
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff8125ee10-ffffffff8125ee71: bpf_tramp_image_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_tramp_image_put(struct bpf_tramp_image *im);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812a9390)
Location: kernel/bpf/trampoline.c:245
Inline: True
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff812a9390-ffffffff812a9411: bpf_tramp_image_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_tramp_image_put(struct bpf_tramp_image *im);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81308170)
Location: kernel/bpf/trampoline.c:327
Inline: True
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff81308170-ffffffff813081f1: bpf_tramp_image_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_tramp_image_put(struct bpf_tramp_image *im);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81337040)
Location: kernel/bpf/trampoline.c:304
Inline: True
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff81337040-ffffffff813370c2: bpf_tramp_image_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_tramp_image_put(struct bpf_tramp_image *im);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8135cec0)
Location: kernel/bpf/trampoline.c:304
Inline: True
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff8135cec0-ffffffff8135cf42: bpf_tramp_image_put (STB_LOCAL)
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
