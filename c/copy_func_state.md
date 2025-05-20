# Function: <code>copy_func_state</code>

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
In kernel/bpf/verifier.c (ffffffff811b77a2)
Location: kernel/bpf/verifier.c:445
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff811c6c94)
Location: kernel/bpf/verifier.c:686
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff811d8ef6)
Location: kernel/bpf/verifier.c:700
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff811e55e6)
Location: kernel/bpf/verifier.c:700
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204bd1)
Location: kernel/bpf/verifier.c:827
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204b91)
Location: kernel/bpf/verifier.c:853
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204aa1)
Location: kernel/bpf/verifier.c:902
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8123687e)
Location: kernel/bpf/verifier.c:918
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127adfe)
Location: kernel/bpf/verifier.c:1145
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_func_state(struct bpf_func_state *dst, const struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d1780)
Location: kernel/bpf/verifier.c:1347
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff812d1780-ffffffff812d1871: copy_func_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_func_state(struct bpf_func_state *dst, const struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812feb90)
Location: kernel/bpf/verifier.c:1724
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff812feb90-ffffffff812fec81: copy_func_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_func_state(struct bpf_func_state *dst, const struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131e270)
Location: kernel/bpf/verifier.c:1377
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff8131e270-ffffffff8131e361: copy_func_state (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffff8000102687fc)
Location: kernel/bpf/verifier.c:700
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (c049aba4)
Location: kernel/bpf/verifier.c:700
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (c00000000030e4b4)
Location: kernel/bpf/verifier.c:700
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffe0001a3954)
Location: kernel/bpf/verifier.c:700
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff811ddc06)
Location: kernel/bpf/verifier.c:700
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff811d09c6)
Location: kernel/bpf/verifier.c:700
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff811db9d6)
Location: kernel/bpf/verifier.c:700
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff811e9de6)
Location: kernel/bpf/verifier.c:700
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
</details>
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
