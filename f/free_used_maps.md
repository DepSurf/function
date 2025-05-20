# Function: <code>free_used_maps</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81172ed0)
Location: kernel/bpf/syscall.c:495
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__prog_put_common
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff81172ed0-ffffffff81172f15: free_used_maps.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81180e10)
Location: kernel/bpf/syscall.c:592
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff81180e10-ffffffff81180e55: free_used_maps.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118ce90)
Location: kernel/bpf/syscall.c:635
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff8118ce90-ffffffff8118ced5: free_used_maps.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191bb0)
Location: kernel/bpf/syscall.c:676
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff81191bb0-ffffffff81191bfa: free_used_maps.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119f020)
Location: kernel/bpf/syscall.c:836
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff8119f020-ffffffff8119f06a: free_used_maps.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b5000)
Location: kernel/bpf/syscall.c:928
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff811b5000-ffffffff811b504a: free_used_maps.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_used_maps(struct bpf_prog_aux *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c33d0)
Location: kernel/bpf/syscall.c:1103
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff811c33d0-ffffffff811c3451: free_used_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_used_maps(struct bpf_prog_aux *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4120)
Location: kernel/bpf/syscall.c:1209
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff811d4120-ffffffff811d41a1: free_used_maps (STB_LOCAL)
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
In kernel/bpf/syscall.c (ffffffff811e04d1)
Location: kernel/bpf/syscall.c:1222
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/bpf/syscall.c (ffff800010262c04)
Location: kernel/bpf/syscall.c:1222
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
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
In kernel/bpf/syscall.c (c049566c)
Location: kernel/bpf/syscall.c:1222
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
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
In kernel/bpf/syscall.c (c000000000307908)
Location: kernel/bpf/syscall.c:1222
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
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
In kernel/bpf/syscall.c (ffffffe00019f484)
Location: kernel/bpf/syscall.c:1222
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
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
In kernel/bpf/syscall.c (ffffffff811d8af1)
Location: kernel/bpf/syscall.c:1222
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
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
In kernel/bpf/syscall.c (ffffffff811cb8b1)
Location: kernel/bpf/syscall.c:1222
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
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
In kernel/bpf/syscall.c (ffffffff811d68c1)
Location: kernel/bpf/syscall.c:1222
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
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
In kernel/bpf/syscall.c (ffffffff811e4c31)
Location: kernel/bpf/syscall.c:1222
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
