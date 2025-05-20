# Function: <code>dev_map_init_map</code>

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
In kernel/bpf/devmap.c (ffffffff811ffa1a)
Location: kernel/bpf/devmap.c:110
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_map_init_map(struct bpf_dtab *dtab, union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812268e0)
Location: kernel/bpf/devmap.c:109
Inline: False
```
**Symbols:**

```
ffffffff812268e0-ffffffff81226a3c: dev_map_init_map (STB_LOCAL)
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
In kernel/bpf/devmap.c (ffffffff8122d66d)
Location: kernel/bpf/devmap.c:109
Inline: True
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
In kernel/bpf/devmap.c (ffffffff81232775)
Location: kernel/bpf/devmap.c:109
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_map_init_map(struct bpf_dtab *dtab, union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:110
Inline: False
```
**Symbols:**

```
ffffffff8126b750-ffffffff8126b885: dev_map_init_map (STB_LOCAL)
ffffffff81cb95e5-ffffffff81cb9603: dev_map_init_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_map_init_map(struct bpf_dtab *dtab, union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:111
Inline: False
```
**Symbols:**

```
ffffffff812ba540-ffffffff812ba687: dev_map_init_map (STB_LOCAL)
ffffffff81e6aa09-ffffffff81e6aa27: dev_map_init_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dev_map_init_map(struct bpf_dtab *dtab, union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:111
Inline: False
```
**Symbols:**

```
ffffffff8131d900-ffffffff8131da47: dev_map_init_map (STB_LOCAL)
ffffffff82061aaa-ffffffff82061ac8: dev_map_init_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dev_map_init_map(struct bpf_dtab *dtab, union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:111
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_alloc
```
**Symbols:**

```
ffffffff8134d700-ffffffff8134d847: dev_map_init_map (STB_LOCAL)
ffffffff820e113e-ffffffff820e115c: dev_map_init_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dev_map_init_map(struct bpf_dtab *dtab, union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:110
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_alloc
```
**Symbols:**

```
ffffffff81374c20-ffffffff81374d67: dev_map_init_map (STB_LOCAL)
ffffffff821bd99d-ffffffff821bd9bb: dev_map_init_map.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int dev_map_init_map(struct bpf_dtab *dtab, union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffff800010286898)
Location: kernel/bpf/devmap.c:110
Inline: False
```
**Symbols:**

```
ffff800010286898-ffff800010286a90: dev_map_init_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_map_init_map(struct bpf_dtab *dtab, union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c04b6f34)
Location: kernel/bpf/devmap.c:110
Inline: False
```
**Symbols:**

```
c04b6f34-c04b711c: dev_map_init_map (STB_LOCAL)
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
In kernel/bpf/devmap.c (c000000000331eb0)
Location: kernel/bpf/devmap.c:110
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_map_init_map(struct bpf_dtab *dtab, union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffe0001bbd48)
Location: kernel/bpf/devmap.c:110
Inline: False
```
**Symbols:**

```
ffffffe0001bbd48-ffffffe0001bbf4a: dev_map_init_map (STB_LOCAL)
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
In kernel/bpf/devmap.c (ffffffff811f803a)
Location: kernel/bpf/devmap.c:110
Inline: True
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
In kernel/bpf/devmap.c (ffffffff811ead8a)
Location: kernel/bpf/devmap.c:110
Inline: True
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
In kernel/bpf/devmap.c (ffffffff811f5e0a)
Location: kernel/bpf/devmap.c:110
Inline: True
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
In kernel/bpf/devmap.c (ffffffff8120436a)
Location: kernel/bpf/devmap.c:110
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Arch</b>
<ul>
</ul>
