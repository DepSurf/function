# Function: <code>xsk_map_sock_delete</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff81200fb0)
Location: kernel/bpf/xskmap.c:66
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81200fb0-ffffffff81201058: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81ba9050)
Location: net/xdp/xskmap.c:59
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81ba9050-ffffffff81ba90f8: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81bb8860)
Location: net/xdp/xskmap.c:44
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81bb8860-ffffffff81bb8908: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81ba7a90)
Location: net/xdp/xskmap.c:44
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81ba7a90-ffffffff81ba7b38: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81c75720)
Location: net/xdp/xskmap.c:44
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81c75720-ffffffff81c757c8: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81e19960)
Location: net/xdp/xskmap.c:46
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81e19960-ffffffff81e19a11: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81ff0d00)
Location: net/xdp/xskmap.c:46
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81ff0d00-ffffffff81ff0db1: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff8206cee0)
Location: net/xdp/xskmap.c:49
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff8206cee0-ffffffff8206cfa9: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff82140d80)
Location: net/xdp/xskmap.c:49
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff82140d80-ffffffff82140e49: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffff800010288ef8)
Location: kernel/bpf/xskmap.c:66
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffff800010288ef8-ffff800010289024: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (c04b8928)
Location: kernel/bpf/xskmap.c:66
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
c04b8928-c04b89cc: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (c000000000334250)
Location: kernel/bpf/xskmap.c:66
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
c000000000334250-c000000000334378: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffe0001bd360)
Location: kernel/bpf/xskmap.c:66
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffe0001bd360-ffffffe0001bd40c: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f95d0)
Location: kernel/bpf/xskmap.c:66
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff811f95d0-ffffffff811f9678: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811ec320)
Location: kernel/bpf/xskmap.c:66
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff811ec320-ffffffff811ec3c8: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f73a0)
Location: kernel/bpf/xskmap.c:66
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff811f73a0-ffffffff811f7448: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xsk_map_sock_delete(struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff81205920)
Location: kernel/bpf/xskmap.c:66
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81205920-ffffffff812059c8: xsk_map_sock_delete (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
