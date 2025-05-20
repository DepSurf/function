# Function: <code>is_valid_dst</code>

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
bool is_valid_dst(struct bpf_dtab_netdev *obj, struct xdp_buff *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8126b1e0)
Location: kernel/bpf/devmap.c:537
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
```
**Symbols:**

```
ffffffff8126b1e0-ffffffff8126b22e: is_valid_dst (STB_LOCAL)
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
In kernel/bpf/devmap.c (ffffffff812bb661)
Location: kernel/bpf/devmap.c:533
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool is_valid_dst(struct bpf_dtab_netdev *obj, struct xdp_frame *xdpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8131d0d0)
Location: kernel/bpf/devmap.c:533
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
```
**Symbols:**

```
ffffffff8131d0d0-ffffffff8131d153: is_valid_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool is_valid_dst(struct bpf_dtab_netdev *obj, struct xdp_frame *xdpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8134ce60)
Location: kernel/bpf/devmap.c:534
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
```
**Symbols:**

```
ffffffff8134ce60-ffffffff8134cef9: is_valid_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool is_valid_dst(struct bpf_dtab_netdev *obj, struct xdp_frame *xdpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81374390)
Location: kernel/bpf/devmap.c:543
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
```
**Symbols:**

```
ffffffff81374390-ffffffff81374426: is_valid_dst (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
