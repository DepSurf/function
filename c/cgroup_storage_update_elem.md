# Function: <code>cgroup_storage_update_elem</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *_key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811d8230)
Location: kernel/bpf/local_storage.c:127
Inline: False
```
**Symbols:**

```
ffffffff811d8230-ffffffff811d82bc: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *_key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ecc50)
Location: kernel/bpf/local_storage.c:127
Inline: False
```
**Symbols:**

```
ffffffff811ecc50-ffffffff811ecd49: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *_key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f93a0)
Location: kernel/bpf/local_storage.c:127
Inline: False
```
**Symbols:**

```
ffffffff811f93a0-ffffffff811f9499: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *_key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121d210)
Location: kernel/bpf/local_storage.c:127
Inline: False
```
**Symbols:**

```
ffffffff8121d210-ffffffff8121d324: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff812200d0)
Location: kernel/bpf/local_storage.c:144
Inline: False
```
**Symbols:**

```
ffffffff812200d0-ffffffff812201dd: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81223b60)
Location: kernel/bpf/local_storage.c:145
Inline: False
```
**Symbols:**

```
ffffffff81223b60-ffffffff81223c6d: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8125b9c0)
Location: kernel/bpf/local_storage.c:143
Inline: False
```
**Symbols:**

```
ffffffff8125b9c0-ffffffff8125baf9: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff812a5440)
Location: kernel/bpf/local_storage.c:144
Inline: False
```
**Symbols:**

```
ffffffff812a5440-ffffffff812a55a5: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81303260)
Location: kernel/bpf/local_storage.c:144
Inline: False
```
**Symbols:**

```
ffffffff81303260-ffffffff813034cb: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int cgroup_storage_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81331d00)
Location: kernel/bpf/local_storage.c:144
Inline: False
```
**Symbols:**

```
ffffffff81331d00-ffffffff81331ef1: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int cgroup_storage_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff813562a0)
Location: kernel/bpf/local_storage.c:144
Inline: False
```
**Symbols:**

```
ffffffff813562a0-ffffffff813564a5: cgroup_storage_update_elem (STB_LOCAL)
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
int cgroup_storage_update_elem(struct bpf_map *map, void *_key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffff80001027ead8)
Location: kernel/bpf/local_storage.c:127
Inline: False
```
**Symbols:**

```
ffff80001027ead8-ffff80001027ec28: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *_key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c04b01b0)
Location: kernel/bpf/local_storage.c:127
Inline: False
```
**Symbols:**

```
c04b01b0-c04b02c8: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *_key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c000000000328b50)
Location: kernel/bpf/local_storage.c:127
Inline: False
```
**Symbols:**

```
c000000000328b50-c000000000328d20: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *_key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffe0001b59b0)
Location: kernel/bpf/local_storage.c:127
Inline: False
```
**Symbols:**

```
ffffffe0001b59b0-ffffffe0001b5a8a: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *_key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f19c0)
Location: kernel/bpf/local_storage.c:127
Inline: False
```
**Symbols:**

```
ffffffff811f19c0-ffffffff811f1ab9: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *_key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811e4710)
Location: kernel/bpf/local_storage.c:127
Inline: False
```
**Symbols:**

```
ffffffff811e4710-ffffffff811e4809: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *_key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ef790)
Location: kernel/bpf/local_storage.c:127
Inline: False
```
**Symbols:**

```
ffffffff811ef790-ffffffff811ef889: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_storage_update_elem(struct bpf_map *map, void *_key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811fdc70)
Location: kernel/bpf/local_storage.c:127
Inline: False
```
**Symbols:**

```
ffffffff811fdc70-ffffffff811fdd69: cgroup_storage_update_elem (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *key</code>
</li>
<li>
<b>Param removed. </b>
<code>void *_key</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
