# Function: <code>__dev_map_update_elem</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ff4aa)
Location: kernel/bpf/devmap.c:623
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8122680f)
Location: kernel/bpf/devmap.c:645
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8122d3ff)
Location: kernel/bpf/devmap.c:631
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812321cf)
Location: kernel/bpf/devmap.c:624
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8126b41f)
Location: kernel/bpf/devmap.c:896
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812ba065)
Location: kernel/bpf/devmap.c:888
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8131d3c5)
Location: kernel/bpf/devmap.c:888
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __dev_map_update_elem(struct net *net, struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8134d130)
Location: kernel/bpf/devmap.c:897
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffffffff8134d130-ffffffff8134d245: __dev_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __dev_map_update_elem(struct net *net, struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81374650)
Location: kernel/bpf/devmap.c:905
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffffffff81374650-ffffffff81374765: __dev_map_update_elem (STB_LOCAL)
```
</details>
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
In kernel/bpf/devmap.c (ffff8000102867a4)
Location: kernel/bpf/devmap.c:623
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
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
In kernel/bpf/devmap.c (c04b73e0)
Location: kernel/bpf/devmap.c:623
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
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
In kernel/bpf/devmap.c (c000000000331a00)
Location: kernel/bpf/devmap.c:623
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
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
In kernel/bpf/devmap.c (ffffffe0001bb7c6)
Location: kernel/bpf/devmap.c:623
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
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
In kernel/bpf/devmap.c (ffffffff811f7aca)
Location: kernel/bpf/devmap.c:623
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
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
In kernel/bpf/devmap.c (ffffffff811ea81a)
Location: kernel/bpf/devmap.c:623
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
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
In kernel/bpf/devmap.c (ffffffff811f589a)
Location: kernel/bpf/devmap.c:623
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
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
In kernel/bpf/devmap.c (ffffffff81203dfa)
Location: kernel/bpf/devmap.c:623
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
