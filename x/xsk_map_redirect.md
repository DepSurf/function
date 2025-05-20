# Function: <code>xsk_map_redirect</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xsk_map_redirect(struct bpf_map *map, u32 ifindex, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81ba7940)
Location: net/xdp/xskmap.c:227
Inline: False
```
**Symbols:**

```
ffffffff81ba7940-ffffffff81ba79a5: xsk_map_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xsk_map_redirect(struct bpf_map *map, u32 ifindex, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81c755c0)
Location: net/xdp/xskmap.c:232
Inline: False
```
**Symbols:**

```
ffffffff81c755c0-ffffffff81c75636: xsk_map_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xsk_map_redirect(struct bpf_map *map, u32 ifindex, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81e197e0)
Location: net/xdp/xskmap.c:234
Inline: False
```
**Symbols:**

```
ffffffff81e197e0-ffffffff81e19877: xsk_map_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xsk_map_redirect(struct bpf_map *map, u64 index, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81ff0b50)
Location: net/xdp/xskmap.c:234
Inline: False
```
**Symbols:**

```
ffffffff81ff0b50-ffffffff81ff0be8: xsk_map_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int xsk_map_redirect(struct bpf_map *map, u64 index, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff8206ccc0)
Location: net/xdp/xskmap.c:242
Inline: False
```
**Symbols:**

```
ffffffff8206ccc0-ffffffff8206cd59: xsk_map_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int xsk_map_redirect(struct bpf_map *map, u64 index, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff82140b60)
Location: net/xdp/xskmap.c:242
Inline: False
```
**Symbols:**

```
ffffffff82140b60-ffffffff82140bf9: xsk_map_redirect (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 index</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 ifindex</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
