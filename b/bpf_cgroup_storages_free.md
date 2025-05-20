# Function: <code>bpf_cgroup_storages_free</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storages_free(struct bpf_cgroup_storage **storages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122dda4)
Location: kernel/bpf/cgroup.c:31
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff8122c060-ffffffff8122c084: bpf_cgroup_storages_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storages_free(struct bpf_cgroup_storage **storages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812360c8)
Location: kernel/bpf/cgroup.c:31
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff812343f0-ffffffff81234414: bpf_cgroup_storages_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storages_free(struct bpf_cgroup_storage **storages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8123a30c)
Location: kernel/bpf/cgroup.c:31
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81238230-ffffffff81238254: bpf_cgroup_storages_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storages_free(struct bpf_cgroup_storage **storages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81274bfe)
Location: kernel/bpf/cgroup.c:31
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81272830-ffffffff81272854: bpf_cgroup_storages_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storages_free(struct bpf_cgroup_storage **storages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c4852)
Location: kernel/bpf/cgroup.c:70
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff812c1c70-ffffffff812c1c9a: bpf_cgroup_storages_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storages_free(struct bpf_cgroup_storage **storages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813290a0)
Location: kernel/bpf/cgroup.c:198
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff813263c0-ffffffff813263ea: bpf_cgroup_storages_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storages_free(struct bpf_cgroup_storage **storages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8135943e)
Location: kernel/bpf/cgroup.c:198
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81356710-ffffffff8135673a: bpf_cgroup_storages_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storages_free(struct bpf_cgroup_storage **storages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81381fed)
Location: kernel/bpf/cgroup.c:198
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff8137f240-ffffffff8137f26a: bpf_cgroup_storages_free (STB_LOCAL)
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
