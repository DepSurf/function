# Function: <code>bpf_test_run_xdp_live</code>

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
int bpf_test_run_xdp_live(struct bpf_prog *prog, struct xdp_buff *ctx, u32 repeat, u32 batch_size, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81cb44b0)
Location: net/bpf/test_run.c:344
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81cb44b0-ffffffff81cb47eb: bpf_test_run_xdp_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_test_run_xdp_live(struct bpf_prog *prog, struct xdp_buff *ctx, u32 repeat, u32 batch_size, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81e72730)
Location: net/bpf/test_run.c:344
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81e72730-ffffffff81e72a6b: bpf_test_run_xdp_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_test_run_xdp_live(struct bpf_prog *prog, struct xdp_buff *ctx, u32 repeat, u32 batch_size, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81ece8d0)
Location: net/bpf/test_run.c:363
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81ece8d0-ffffffff81ecebc7: bpf_test_run_xdp_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_test_run_xdp_live(struct bpf_prog *prog, struct xdp_buff *ctx, u32 repeat, u32 batch_size, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81f92100)
Location: net/bpf/test_run.c:364
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81f92100-ffffffff81f923f7: bpf_test_run_xdp_live (STB_LOCAL)
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
