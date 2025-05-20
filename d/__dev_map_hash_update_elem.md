# Function: <code>__dev_map_hash_update_elem</code>

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
In kernel/bpf/devmap.c (ffffffff811ff573)
Location: kernel/bpf/devmap.c:664
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __dev_map_hash_update_elem(struct net *net, struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:692
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
**Symbols:**

```
ffffffff81227350-ffffffff8122757e: __dev_map_hash_update_elem (STB_LOCAL)
ffffffff812279bd-ffffffff812279c9: __dev_map_hash_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __dev_map_hash_update_elem(struct net *net, struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:678
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
**Symbols:**

```
ffffffff8122dea0-ffffffff8122e0ce: __dev_map_hash_update_elem (STB_LOCAL)
ffffffff81be65fa-ffffffff81be6606: __dev_map_hash_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __dev_map_hash_update_elem(struct net *net, struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:671
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
**Symbols:**

```
ffffffff812322a0-ffffffff812324ba: __dev_map_hash_update_elem (STB_LOCAL)
ffffffff81bd82fa-ffffffff81bd8306: __dev_map_hash_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __dev_map_hash_update_elem(struct net *net, struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:943
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
**Symbols:**

```
ffffffff8126b4f0-ffffffff8126b70a: __dev_map_hash_update_elem (STB_LOCAL)
ffffffff81cb95d9-ffffffff81cb95e5: __dev_map_hash_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __dev_map_hash_update_elem(struct net *net, struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:935
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
**Symbols:**

```
ffffffff812ba130-ffffffff812ba356: __dev_map_hash_update_elem (STB_LOCAL)
ffffffff81e6a9fd-ffffffff81e6aa09: __dev_map_hash_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dev_map_hash_update_elem(struct net *net, struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8131d4b0)
Location: kernel/bpf/devmap.c:935
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
**Symbols:**

```
ffffffff8131d4b0-ffffffff8131d6e2: __dev_map_hash_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __dev_map_hash_update_elem(struct net *net, struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8134d2c0)
Location: kernel/bpf/devmap.c:946
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
**Symbols:**

```
ffffffff8134d2c0-ffffffff8134d4ed: __dev_map_hash_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __dev_map_hash_update_elem(struct net *net, struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff813747e0)
Location: kernel/bpf/devmap.c:954
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
**Symbols:**

```
ffffffff813747e0-ffffffff81374a0d: __dev_map_hash_update_elem (STB_LOCAL)
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
In kernel/bpf/devmap.c (ffff800010287344)
Location: kernel/bpf/devmap.c:664
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
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
In kernel/bpf/devmap.c (c04b6b90)
Location: kernel/bpf/devmap.c:664
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
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
In kernel/bpf/devmap.c (c000000000331b98)
Location: kernel/bpf/devmap.c:664
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
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
In kernel/bpf/devmap.c (ffffffe0001bb872)
Location: kernel/bpf/devmap.c:664
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
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
In kernel/bpf/devmap.c (ffffffff811f7b93)
Location: kernel/bpf/devmap.c:664
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
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
In kernel/bpf/devmap.c (ffffffff811ea8e3)
Location: kernel/bpf/devmap.c:664
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
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
In kernel/bpf/devmap.c (ffffffff811f5963)
Location: kernel/bpf/devmap.c:664
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
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
In kernel/bpf/devmap.c (ffffffff81203ec3)
Location: kernel/bpf/devmap.c:664
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
```
</details>
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
