# Function: <code>dev_map_bpf_prog_run</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_map_bpf_prog_run(struct bpf_prog *xdp_prog, struct xdp_frame **frames, int n, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8126bba0)
Location: kernel/bpf/devmap.c:325
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
**Symbols:**

```
ffffffff8126bba0-ffffffff8126be69: dev_map_bpf_prog_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_map_bpf_prog_run(struct bpf_prog *xdp_prog, struct xdp_frame **frames, int n, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812ba9c0)
Location: kernel/bpf/devmap.c:326
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
**Symbols:**

```
ffffffff812ba9c0-ffffffff812bacce: dev_map_bpf_prog_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_map_bpf_prog_run(struct bpf_prog *xdp_prog, struct xdp_frame **frames, int n, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8131ddb0)
Location: kernel/bpf/devmap.c:326
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
**Symbols:**

```
ffffffff8131ddb0-ffffffff8131e0b2: dev_map_bpf_prog_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_map_bpf_prog_run(struct bpf_prog *xdp_prog, struct xdp_frame **frames, int n, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8134dba0)
Location: kernel/bpf/devmap.c:323
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
**Symbols:**

```
ffffffff8134dba0-ffffffff8134dea2: dev_map_bpf_prog_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_map_bpf_prog_run(struct bpf_prog *xdp_prog, struct xdp_frame **frames, int n, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff813750b0)
Location: kernel/bpf/devmap.c:322
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
**Symbols:**

```
ffffffff813750b0-ffffffff813753ae: dev_map_bpf_prog_run (STB_LOCAL)
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
