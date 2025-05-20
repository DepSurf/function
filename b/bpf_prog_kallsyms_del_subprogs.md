# Function: <code>bpf_prog_kallsyms_del_subprogs</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_prog_kallsyms_del_subprogs(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b1ed0)
Location: kernel/bpf/core.c:353
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811b1ed0-ffffffff811b1f0f: bpf_prog_kallsyms_del_subprogs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_prog_kallsyms_del_subprogs(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c0780)
Location: kernel/bpf/core.c:463
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811c0780-ffffffff811c07bf: bpf_prog_kallsyms_del_subprogs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_prog_kallsyms_del_subprogs(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d12c0)
Location: kernel/bpf/core.c:505
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811d12c0-ffffffff811d12ff: bpf_prog_kallsyms_del_subprogs (STB_GLOBAL)
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
In kernel/bpf/core.c (ffffffff811dd855)
Location: kernel/bpf/core.c:505
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In kernel/bpf/core.c (ffffffff811fa135)
Location: kernel/bpf/core.c:505
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In kernel/bpf/core.c (ffffffff811f9165)
Location: kernel/bpf/core.c:501
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In kernel/bpf/core.c (ffffffff811f9f45)
Location: kernel/bpf/core.c:507
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In kernel/bpf/core.c (ffffffff8122b615)
Location: kernel/bpf/core.c:507
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In kernel/bpf/core.c (ffffffff8126d085)
Location: kernel/bpf/core.c:519
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c21d5)
Location: kernel/bpf/core.c:527
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e9095)
Location: kernel/bpf/core.c:528
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81307405)
Location: kernel/bpf/core.c:545
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In kernel/bpf/core.c (ffff80001025e538)
Location: kernel/bpf/core.c:505
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In kernel/bpf/core.c (c0491c4c)
Location: kernel/bpf/core.c:505
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In kernel/bpf/core.c (c000000000303278)
Location: kernel/bpf/core.c:505
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In kernel/bpf/core.c (ffffffe00019c906)
Location: kernel/bpf/core.c:505
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In kernel/bpf/core.c (ffffffff811d5e75)
Location: kernel/bpf/core.c:505
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In kernel/bpf/core.c (ffffffff811c8c35)
Location: kernel/bpf/core.c:505
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In kernel/bpf/core.c (ffffffff811d3c45)
Location: kernel/bpf/core.c:505
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In kernel/bpf/core.c (ffffffff811e1f35)
Location: kernel/bpf/core.c:505
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
