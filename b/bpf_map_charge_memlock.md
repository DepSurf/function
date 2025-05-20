# Function: <code>bpf_map_charge_memlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8117387b)
Location: kernel/bpf/syscall.c:49
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81181a8a)
Location: kernel/bpf/syscall.c:64
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118dcb1)
Location: kernel/bpf/syscall.c:92
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81192a94)
Location: kernel/bpf/syscall.c:103
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811a0d54)
Location: kernel/bpf/syscall.c:150
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b5349)
Location: kernel/bpf/syscall.c:184
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c3270)
Location: kernel/bpf/syscall.c:221
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811c3270-ffffffff811c329b: bpf_map_charge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d3fc0)
Location: kernel/bpf/syscall.c:237
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811d3fc0-ffffffff811d3fe8: bpf_map_charge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e0350)
Location: kernel/bpf/syscall.c:240
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811e0350-ffffffff811e0378: bpf_map_charge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe870)
Location: kernel/bpf/syscall.c:394
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811fe870-ffffffff811fe8bf: bpf_map_charge_memlock (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010262958)
Location: kernel/bpf/syscall.c:240
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffff800010262958-ffff80001026299c: bpf_map_charge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c04954a0)
Location: kernel/bpf/syscall.c:240
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
c04954a0-c04954d8: bpf_map_charge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000307650)
Location: kernel/bpf/syscall.c:240
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
c000000000307650-c0000000003076c8: bpf_map_charge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019f26c)
Location: kernel/bpf/syscall.c:240
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffe00019f26c-ffffffe00019f2ce: bpf_map_charge_memlock (STB_GLOBAL)
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
int bpf_map_charge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8970)
Location: kernel/bpf/syscall.c:240
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811d8970-ffffffff811d8998: bpf_map_charge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cb730)
Location: kernel/bpf/syscall.c:240
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811cb730-ffffffff811cb758: bpf_map_charge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6740)
Location: kernel/bpf/syscall.c:240
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811d6740-ffffffff811d6768: bpf_map_charge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e4ab0)
Location: kernel/bpf/syscall.c:240
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811e4ab0-ffffffff811e4ad8: bpf_map_charge_memlock (STB_GLOBAL)
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
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
