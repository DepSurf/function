# Function: <code>bpf_iter_attach_map</code>

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
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int bpf_iter_attach_map(struct bpf_prog *prog, union bpf_iter_link_info *linfo, struct bpf_iter_aux_info *aux);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff812181d0)
Location: kernel/bpf/map_iter.c:101
Inline: False
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69700)
Location: net/core/bpf_sk_storage.c:873
Inline: False
```
**Symbols:**

```
ffffffff812181d0-ffffffff812182b6: bpf_iter_attach_map (STB_LOCAL)
ffffffff81a69700-ffffffff81a69771: bpf_iter_attach_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int bpf_iter_attach_map(struct bpf_prog *prog, union bpf_iter_link_info *linfo, struct bpf_iter_aux_info *aux);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff8121b620)
Location: kernel/bpf/map_iter.c:101
Inline: False
```
```
In net/core/bpf_sk_storage.c (ffffffff81a51ea0)
Location: net/core/bpf_sk_storage.c:873
Inline: False
```
**Symbols:**

```
ffffffff8121b620-ffffffff8121b706: bpf_iter_attach_map (STB_LOCAL)
ffffffff81a51ea0-ffffffff81a51f11: bpf_iter_attach_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
int bpf_iter_attach_map(struct bpf_prog *prog, union bpf_iter_link_info *linfo, struct bpf_iter_aux_info *aux);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff81252520)
Location: kernel/bpf/map_iter.c:101
Inline: False
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0ab30)
Location: net/core/bpf_sk_storage.c:872
Inline: False
```
**Symbols:**

```
ffffffff81252520-ffffffff81252606: bpf_iter_attach_map (STB_LOCAL)
ffffffff81b0ab30-ffffffff81b0aba1: bpf_iter_attach_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int bpf_iter_attach_map(struct bpf_prog *prog, union bpf_iter_link_info *linfo, struct bpf_iter_aux_info *aux);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff8129a330)
Location: kernel/bpf/map_iter.c:101
Inline: False
```
```
In net/core/bpf_sk_storage.c (ffffffff81c911e0)
Location: net/core/bpf_sk_storage.c:891
Inline: False
```
**Symbols:**

```
ffffffff8129a330-ffffffff8129a423: bpf_iter_attach_map (STB_LOCAL)
ffffffff81c911e0-ffffffff81c9125e: bpf_iter_attach_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int bpf_iter_attach_map(struct bpf_prog *prog, union bpf_iter_link_info *linfo, struct bpf_iter_aux_info *aux);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff812f6320)
Location: kernel/bpf/map_iter.c:101
Inline: False
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4c640)
Location: net/core/bpf_sk_storage.c:861
Inline: False
```
**Symbols:**

```
ffffffff812f6320-ffffffff812f6413: bpf_iter_attach_map (STB_LOCAL)
ffffffff81e4c640-ffffffff81e4c6be: bpf_iter_attach_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int bpf_iter_attach_map(struct bpf_prog *prog, union bpf_iter_link_info *linfo, struct bpf_iter_aux_info *aux);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff813241d0)
Location: kernel/bpf/map_iter.c:101
Inline: False
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea7d60)
Location: net/core/bpf_sk_storage.c:859
Inline: False
```
**Symbols:**

```
ffffffff813241d0-ffffffff813242d6: bpf_iter_attach_map (STB_LOCAL)
ffffffff81ea7d60-ffffffff81ea7dde: bpf_iter_attach_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int bpf_iter_attach_map(struct bpf_prog *prog, union bpf_iter_link_info *linfo, struct bpf_iter_aux_info *aux);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff813481a0)
Location: kernel/bpf/map_iter.c:100
Inline: False
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6a810)
Location: net/core/bpf_sk_storage.c:860
Inline: False
```
**Symbols:**

```
ffffffff813481a0-ffffffff813482a6: bpf_iter_attach_map (STB_LOCAL)
ffffffff81f6a810-ffffffff81f6a88e: bpf_iter_attach_map (STB_LOCAL)
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
