# Function: <code>ringbuf_map_update_elem</code>

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
int ringbuf_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff8121deb0)
Location: kernel/bpf/ringbuf.c:233
Inline: False
```
**Symbols:**

```
ffffffff8121deb0-ffffffff8121dec0: ringbuf_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ringbuf_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81220c50)
Location: kernel/bpf/ringbuf.c:207
Inline: False
```
**Symbols:**

```
ffffffff81220c50-ffffffff81220c60: ringbuf_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ringbuf_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff812246e0)
Location: kernel/bpf/ringbuf.c:209
Inline: False
```
**Symbols:**

```
ffffffff812246e0-ffffffff812246f0: ringbuf_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ringbuf_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff8125c620)
Location: kernel/bpf/ringbuf.c:209
Inline: False
```
**Symbols:**

```
ffffffff8125c620-ffffffff8125c630: ringbuf_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ringbuf_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff812a6310)
Location: kernel/bpf/ringbuf.c:210
Inline: False
```
**Symbols:**

```
ffffffff812a6310-ffffffff812a6324: ringbuf_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ringbuf_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81304440)
Location: kernel/bpf/ringbuf.c:244
Inline: False
```
**Symbols:**

```
ffffffff81304440-ffffffff81304454: ringbuf_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int ringbuf_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81332dd0)
Location: kernel/bpf/ringbuf.c:245
Inline: False
```
**Symbols:**

```
ffffffff81332dd0-ffffffff81332de6: ringbuf_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int ringbuf_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff813574c0)
Location: kernel/bpf/ringbuf.c:241
Inline: False
```
**Symbols:**

```
ffffffff813574c0-ffffffff813574d6: ringbuf_map_update_elem (STB_LOCAL)
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
