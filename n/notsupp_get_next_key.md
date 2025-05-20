# Function: <code>notsupp_get_next_key</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81952ad0)
Location: net/core/bpf_sk_storage.c:668
Inline: False
```
**Symbols:**

```
ffffffff81952ad0-ffffffff81952ae0: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81988e20)
Location: net/core/bpf_sk_storage.c:678
Inline: False
```
**Symbols:**

```
ffffffff81988e20-ffffffff81988e30: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a60ac0)
Location: net/core/bpf_sk_storage.c:682
Inline: False
```
**Symbols:**

```
ffffffff81a60ac0-ffffffff81a60ad0: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff812213b0)
Location: kernel/bpf/bpf_inode_storage.c:216
Inline: False
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff812217e0)
Location: kernel/bpf/bpf_task_storage.c:256
Inline: False
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69230)
Location: net/core/bpf_sk_storage.c:107
Inline: False
```
**Symbols:**

```
ffffffff812213b0-ffffffff812213c0: notsupp_get_next_key (STB_LOCAL)
ffffffff812217e0-ffffffff812217f0: notsupp_get_next_key (STB_LOCAL)
ffffffff81a69230-ffffffff81a69240: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81225ae0)
Location: kernel/bpf/bpf_task_storage.c:278
Inline: False
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff81226070)
Location: kernel/bpf/bpf_inode_storage.c:216
Inline: False
```
```
In net/core/bpf_sk_storage.c (ffffffff81a519b0)
Location: net/core/bpf_sk_storage.c:107
Inline: False
```
**Symbols:**

```
ffffffff81225ae0-ffffffff81225af0: notsupp_get_next_key (STB_LOCAL)
ffffffff81226070-ffffffff81226080: notsupp_get_next_key (STB_LOCAL)
ffffffff81a519b0-ffffffff81a519c0: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff8125db00)
Location: kernel/bpf/bpf_task_storage.c:278
Inline: False
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff8125e090)
Location: kernel/bpf/bpf_inode_storage.c:216
Inline: False
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0a4f0)
Location: net/core/bpf_sk_storage.c:107
Inline: False
```
**Symbols:**

```
ffffffff8125db00-ffffffff8125db10: notsupp_get_next_key (STB_LOCAL)
ffffffff8125e090-ffffffff8125e0a0: notsupp_get_next_key (STB_LOCAL)
ffffffff81b0a4f0-ffffffff81b0a500: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff812a7e50)
Location: kernel/bpf/bpf_task_storage.c:284
Inline: False
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff812a84a0)
Location: kernel/bpf/bpf_inode_storage.c:221
Inline: False
```
```
In net/core/bpf_sk_storage.c (ffffffff81c90a50)
Location: net/core/bpf_sk_storage.c:109
Inline: False
```
**Symbols:**

```
ffffffff812a7e50-ffffffff812a7e64: notsupp_get_next_key (STB_LOCAL)
ffffffff812a84a0-ffffffff812a84b4: notsupp_get_next_key (STB_LOCAL)
ffffffff81c90a50-ffffffff81c90a64: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81306660)
Location: kernel/bpf/bpf_task_storage.c:312
Inline: False
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff81306ee0)
Location: kernel/bpf/bpf_inode_storage.c:200
Inline: False
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff813256d0)
Location: kernel/bpf/bpf_cgrp_storage.c:152
Inline: False
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4bed0)
Location: net/core/bpf_sk_storage.c:80
Inline: False
```
**Symbols:**

```
ffffffff81306660-ffffffff81306674: notsupp_get_next_key (STB_LOCAL)
ffffffff81306ee0-ffffffff81306ef4: notsupp_get_next_key (STB_LOCAL)
ffffffff813256d0-ffffffff813256e4: notsupp_get_next_key (STB_LOCAL)
ffffffff81e4bed0-ffffffff81e4bee4: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff813355d0)
Location: kernel/bpf/bpf_task_storage.c:305
Inline: False
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff81335dc0)
Location: kernel/bpf/bpf_inode_storage.c:186
Inline: False
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81355910)
Location: kernel/bpf/bpf_cgrp_storage.c:145
Inline: False
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea75d0)
Location: net/core/bpf_sk_storage.c:74
Inline: False
```
**Symbols:**

```
ffffffff813355d0-ffffffff813355e4: notsupp_get_next_key (STB_LOCAL)
ffffffff81335dc0-ffffffff81335dd4: notsupp_get_next_key (STB_LOCAL)
ffffffff81355910-ffffffff81355924: notsupp_get_next_key (STB_LOCAL)
ffffffff81ea75d0-ffffffff81ea75e4: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81359c30)
Location: kernel/bpf/bpf_task_storage.c:305
Inline: False
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff8135a420)
Location: kernel/bpf/bpf_inode_storage.c:186
Inline: False
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff8137e440)
Location: kernel/bpf/bpf_cgrp_storage.c:145
Inline: False
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6a080)
Location: net/core/bpf_sk_storage.c:74
Inline: False
```
**Symbols:**

```
ffffffff81359c30-ffffffff81359c44: notsupp_get_next_key (STB_LOCAL)
ffffffff8135a420-ffffffff8135a434: notsupp_get_next_key (STB_LOCAL)
ffffffff8137e440-ffffffff8137e454: notsupp_get_next_key (STB_LOCAL)
ffffffff81f6a080-ffffffff81f6a094: notsupp_get_next_key (STB_LOCAL)
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
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffff800010c30e90)
Location: net/core/bpf_sk_storage.c:678
Inline: False
```
**Symbols:**

```
ffff800010c30e90-ffff800010c30eac: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c0d47edc)
Location: net/core/bpf_sk_storage.c:678
Inline: False
```
**Symbols:**

```
c0d47edc-c0d47efc: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c000000000d2a090)
Location: net/core/bpf_sk_storage.c:678
Inline: False
```
**Symbols:**

```
c000000000d2a090-c000000000d2a0a0: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffe0007a6f2c)
Location: net/core/bpf_sk_storage.c:678
Inline: False
```
**Symbols:**

```
ffffffe0007a6f2c-ffffffe0007a6f4a: notsupp_get_next_key (STB_LOCAL)
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
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81928c90)
Location: net/core/bpf_sk_storage.c:678
Inline: False
```
**Symbols:**

```
ffffffff81928c90-ffffffff81928ca0: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff818e2a40)
Location: net/core/bpf_sk_storage.c:678
Inline: False
```
**Symbols:**

```
ffffffff818e2a40-ffffffff818e2a50: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81979e20)
Location: net/core/bpf_sk_storage.c:678
Inline: False
```
**Symbols:**

```
ffffffff81979e20-ffffffff81979e30: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int notsupp_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8199c350)
Location: net/core/bpf_sk_storage.c:678
Inline: False
```
**Symbols:**

```
ffffffff8199c350-ffffffff8199c360: notsupp_get_next_key (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
