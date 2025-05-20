# Function: <code>check_func_proto</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811baece)
Location: kernel/bpf/verifier.c:2272
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cab2d)
Location: kernel/bpf/verifier.c:2600
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e1c0d)
Location: kernel/bpf/verifier.c:3672
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ee40d)
Location: kernel/bpf/verifier.c:3675
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_func_proto(const struct bpf_func_proto *fn, int func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203720)
Location: kernel/bpf/verifier.c:4252
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81203720-ffffffff812038b8: check_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_func_proto(const struct bpf_func_proto *fn, int func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203920)
Location: kernel/bpf/verifier.c:4674
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81203920-ffffffff81203b01: check_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_func_proto(const struct bpf_func_proto *fn, int func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204580)
Location: kernel/bpf/verifier.c:5428
Inline: False
```
**Symbols:**

```
ffffffff81204580-ffffffff8120476e: check_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_func_proto(const struct bpf_func_proto *fn, int func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81237380)
Location: kernel/bpf/verifier.c:5625
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81237380-ffffffff8123768c: check_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81279ec0)
Location: kernel/bpf/verifier.c:6478
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81279ec0-ffffffff8127a22e: check_func_proto.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d1c80)
Location: kernel/bpf/verifier.c:7216
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff812d1c80-ffffffff812d1fa2: check_func_proto.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81303f60)
Location: kernel/bpf/verifier.c:8582
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81303f60-ffffffff81304282: check_func_proto.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81323870)
Location: kernel/bpf/verifier.c:9099
Inline: True
```
**Symbols:**

```
ffffffff81323870-ffffffff81323b92: check_func_proto.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010271e0c)
Location: kernel/bpf/verifier.c:3675
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a4164)
Location: kernel/bpf/verifier.c:3675
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000319330)
Location: kernel/bpf/verifier.c:3675
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001aafe2)
Location: kernel/bpf/verifier.c:3675
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e6a2d)
Location: kernel/bpf/verifier.c:3675
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d97ed)
Location: kernel/bpf/verifier.c:3675
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e47fd)
Location: kernel/bpf/verifier.c:3675
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811f2bcd)
Location: kernel/bpf/verifier.c:3675
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
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
</ul>
