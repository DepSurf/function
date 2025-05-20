# Function: <code>__bpf_map_put</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_map_put(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191950)
Location: kernel/bpf/syscall.c:181
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff81191950-ffffffff811919e1: __bpf_map_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_map_put(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119e890)
Location: kernel/bpf/syscall.c:231
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff8119e890-ffffffff8119e92f: __bpf_map_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_map_put(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b4f60)
Location: kernel/bpf/syscall.c:276
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811b4f60-ffffffff811b4fd7: __bpf_map_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_map_put(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c3330)
Location: kernel/bpf/syscall.c:304
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:free_used_maps
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811c3330-ffffffff811c33a7: __bpf_map_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __bpf_map_put(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4080)
Location: kernel/bpf/syscall.c:322
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:free_used_maps
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811d4080-ffffffff811d40f5: __bpf_map_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __bpf_map_put(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e0410)
Location: kernel/bpf/syscall.c:325
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811e0410-ffffffff811e0485: __bpf_map_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fca65)
Location: kernel/bpf/syscall.c:479
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
**Symbols:**

```
ffffffff811fcb10-ffffffff811fcbbc: __bpf_map_put.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fbdb0)
Location: kernel/bpf/syscall.c:473
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
**Symbols:**

```
ffffffff811fbdb0-ffffffff811fbe5c: __bpf_map_put.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fcaf0)
Location: kernel/bpf/syscall.c:474
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
**Symbols:**

```
ffffffff811fcaf0-ffffffff811fcb9c: __bpf_map_put.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122e630)
Location: kernel/bpf/syscall.c:493
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
**Symbols:**

```
ffffffff8122e630-ffffffff8122e6dc: __bpf_map_put.constprop.0 (STB_LOCAL)
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
In kernel/bpf/syscall.c (ffffffff81270c10)
Location: kernel/bpf/syscall.c:614
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
**Symbols:**

```
ffffffff81270c10-ffffffff81270cd4: __bpf_map_put.constprop.0 (STB_LOCAL)
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
In kernel/bpf/syscall.c (ffffffff812c6c20)
Location: kernel/bpf/syscall.c:711
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
**Symbols:**

```
ffffffff812c6c20-ffffffff812c6ce4: __bpf_map_put.constprop.0 (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_map_put(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010262b08)
Location: kernel/bpf/syscall.c:325
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffff800010262b08-ffff800010262bb0: __bpf_map_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __bpf_map_put(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c049559c)
Location: kernel/bpf/syscall.c:325
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
c049559c-c0495628: __bpf_map_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __bpf_map_put(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0000000003077f0)
Location: kernel/bpf/syscall.c:325
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
**Symbols:**

```
c0000000003077f0-c0000000003078a8: __bpf_map_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019f4b0)
Location: kernel/bpf/syscall.c:325
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
**Symbols:**

```
ffffffe00019f3a2-ffffffe00019f40e: __bpf_map_put.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __bpf_map_put(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8a30)
Location: kernel/bpf/syscall.c:325
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811d8a30-ffffffff811d8aa5: __bpf_map_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __bpf_map_put(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cb7f0)
Location: kernel/bpf/syscall.c:325
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811cb7f0-ffffffff811cb865: __bpf_map_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __bpf_map_put(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6800)
Location: kernel/bpf/syscall.c:325
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811d6800-ffffffff811d6875: __bpf_map_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __bpf_map_put(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e4b70)
Location: kernel/bpf/syscall.c:325
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811e4b70-ffffffff811e4be5: __bpf_map_put (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
