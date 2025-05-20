# Function: <code>ringbuf_map_lookup_elem</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void *ringbuf_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff8121de90)
Location: kernel/bpf/ringbuf.c:228
Inline: False
```
**Symbols:**

```
ffffffff8121de90-ffffffff8121dea2: ringbuf_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *ringbuf_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81220c30)
Location: kernel/bpf/ringbuf.c:202
Inline: False
```
**Symbols:**

```
ffffffff81220c30-ffffffff81220c42: ringbuf_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *ringbuf_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff812246c0)
Location: kernel/bpf/ringbuf.c:204
Inline: False
```
**Symbols:**

```
ffffffff812246c0-ffffffff812246d2: ringbuf_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *ringbuf_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff8125c600)
Location: kernel/bpf/ringbuf.c:204
Inline: False
```
**Symbols:**

```
ffffffff8125c600-ffffffff8125c612: ringbuf_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *ringbuf_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff812a62f0)
Location: kernel/bpf/ringbuf.c:205
Inline: False
```
**Symbols:**

```
ffffffff812a62f0-ffffffff812a6306: ringbuf_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *ringbuf_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81304410)
Location: kernel/bpf/ringbuf.c:239
Inline: False
```
**Symbols:**

```
ffffffff81304410-ffffffff81304426: ringbuf_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *ringbuf_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81332da0)
Location: kernel/bpf/ringbuf.c:240
Inline: False
```
**Symbols:**

```
ffffffff81332da0-ffffffff81332db6: ringbuf_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *ringbuf_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81357490)
Location: kernel/bpf/ringbuf.c:236
Inline: False
```
**Symbols:**

```
ffffffff81357490-ffffffff813574a6: ringbuf_map_lookup_elem (STB_LOCAL)
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
