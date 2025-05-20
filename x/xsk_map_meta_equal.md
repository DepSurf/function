# Function: <code>xsk_map_meta_equal</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
bool xsk_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81bb8760)
Location: net/xdp/xskmap.c:229
Inline: False
```
**Symbols:**

```
ffffffff81bb8760-ffffffff81bb877b: xsk_map_meta_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool xsk_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81ba7920)
Location: net/xdp/xskmap.c:243
Inline: False
```
**Symbols:**

```
ffffffff81ba7920-ffffffff81ba793b: xsk_map_meta_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool xsk_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81c755a0)
Location: net/xdp/xskmap.c:249
Inline: False
```
**Symbols:**

```
ffffffff81c755a0-ffffffff81c755bb: xsk_map_meta_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool xsk_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81e197b0)
Location: net/xdp/xskmap.c:251
Inline: False
```
**Symbols:**

```
ffffffff81e197b0-ffffffff81e197df: xsk_map_meta_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool xsk_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81ff0b10)
Location: net/xdp/xskmap.c:251
Inline: False
```
**Symbols:**

```
ffffffff81ff0b10-ffffffff81ff0b3f: xsk_map_meta_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool xsk_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff8206cdb0)
Location: net/xdp/xskmap.c:259
Inline: False
```
**Symbols:**

```
ffffffff8206cdb0-ffffffff8206cddf: xsk_map_meta_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool xsk_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff82140c50)
Location: net/xdp/xskmap.c:259
Inline: False
```
**Symbols:**

```
ffffffff82140c50-ffffffff82140c7f: xsk_map_meta_equal (STB_LOCAL)
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
