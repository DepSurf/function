# Function: <code>sock_map_iter_detach_target</code>

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
void sock_map_iter_detach_target(struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a53b70)
Location: net/core/sock_map.c:1577
Inline: False
```
**Symbols:**

```
ffffffff81a53b70-ffffffff81a53b83: sock_map_iter_detach_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sock_map_iter_detach_target(struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4f670)
Location: net/core/sock_map.c:1571
Inline: False
```
**Symbols:**

```
ffffffff81a4f670-ffffffff81a4f683: sock_map_iter_detach_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sock_map_iter_detach_target(struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81b082b0)
Location: net/core/sock_map.c:1564
Inline: False
```
**Symbols:**

```
ffffffff81b082b0-ffffffff81b082c3: sock_map_iter_detach_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sock_map_iter_detach_target(struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81c8df40)
Location: net/core/sock_map.c:1637
Inline: False
```
**Symbols:**

```
ffffffff81c8df40-ffffffff81c8df59: sock_map_iter_detach_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sock_map_iter_detach_target(struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e48ec0)
Location: net/core/sock_map.c:1670
Inline: False
```
**Symbols:**

```
ffffffff81e48ec0-ffffffff81e48ed9: sock_map_iter_detach_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sock_map_iter_detach_target(struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea45e0)
Location: net/core/sock_map.c:1685
Inline: False
```
**Symbols:**

```
ffffffff81ea45e0-ffffffff81ea45f9: sock_map_iter_detach_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sock_map_iter_detach_target(struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f67000)
Location: net/core/sock_map.c:1691
Inline: False
```
**Symbols:**

```
ffffffff81f67000-ffffffff81f67019: sock_map_iter_detach_target (STB_LOCAL)
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
