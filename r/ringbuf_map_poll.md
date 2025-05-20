# Function: <code>ringbuf_map_poll</code>

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
__poll_t ringbuf_map_poll(struct bpf_map *map, struct file *filp, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff8121dee0)
Location: kernel/bpf/ringbuf.c:282
Inline: False
```
**Symbols:**

```
ffffffff8121dee0-ffffffff8121df39: ringbuf_map_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__poll_t ringbuf_map_poll(struct bpf_map *map, struct file *filp, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81220c80)
Location: kernel/bpf/ringbuf.c:256
Inline: False
```
**Symbols:**

```
ffffffff81220c80-ffffffff81220cd9: ringbuf_map_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__poll_t ringbuf_map_poll(struct bpf_map *map, struct file *filp, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81224710)
Location: kernel/bpf/ringbuf.c:253
Inline: False
```
**Symbols:**

```
ffffffff81224710-ffffffff81224769: ringbuf_map_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__poll_t ringbuf_map_poll(struct bpf_map *map, struct file *filp, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff8125c650)
Location: kernel/bpf/ringbuf.c:253
Inline: False
```
**Symbols:**

```
ffffffff8125c650-ffffffff8125c6a9: ringbuf_map_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__poll_t ringbuf_map_poll(struct bpf_map *map, struct file *filp, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff812a6370)
Location: kernel/bpf/ringbuf.c:254
Inline: False
```
**Symbols:**

```
ffffffff812a6370-ffffffff812a63d3: ringbuf_map_poll (STB_LOCAL)
```
</details>
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
</ul>
