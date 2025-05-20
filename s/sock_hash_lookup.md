# Function: <code>sock_hash_lookup</code>

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
void *sock_hash_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4ef90)
Location: net/core/sock_map.c:1123
Inline: False
```
**Symbols:**

```
ffffffff81a4ef90-ffffffff81a4f02a: sock_hash_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *sock_hash_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a54b70)
Location: net/core/sock_map.c:1211
Inline: False
```
**Symbols:**

```
ffffffff81a54b70-ffffffff81a54bf8: sock_hash_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *sock_hash_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a51030)
Location: net/core/sock_map.c:1196
Inline: False
```
**Symbols:**

```
ffffffff81a51030-ffffffff81a510b4: sock_hash_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *sock_hash_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:1187
Inline: False
```
**Symbols:**

```
ffffffff81b09370-ffffffff81b09401: sock_hash_lookup (STB_LOCAL)
ffffffff81d38b11-ffffffff81d38b31: sock_hash_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *sock_hash_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:1189
Inline: False
```
**Symbols:**

```
ffffffff81c8f440-ffffffff81c8f4de: sock_hash_lookup (STB_LOCAL)
ffffffff81f0536b-ffffffff81f0538b: sock_hash_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *sock_hash_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:1191
Inline: False
```
**Symbols:**

```
ffffffff81e4a6e0-ffffffff81e4a793: sock_hash_lookup (STB_LOCAL)
ffffffff820ad378-ffffffff820ad398: sock_hash_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *sock_hash_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:1194
Inline: False
```
**Symbols:**

```
ffffffff81ea5df0-ffffffff81ea5e9b: sock_hash_lookup (STB_LOCAL)
ffffffff8212e527-ffffffff8212e540: sock_hash_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *sock_hash_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:1198
Inline: False
```
**Symbols:**

```
ffffffff81f688b0-ffffffff81f6895b: sock_hash_lookup (STB_LOCAL)
ffffffff8221030c-ffffffff82210325: sock_hash_lookup.cold (STB_LOCAL)
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
