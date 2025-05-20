# Function: <code>__hw_addr_create</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev_addr_lists.c (ffffffff81aa80b6)
Location: net/core/dev_addr_lists.c:20
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
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
In net/core/dev_addr_lists.c (ffffffff81c2003d)
Location: net/core/dev_addr_lists.c:51
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct netdev_hw_addr *__hw_addr_create(const unsigned char *addr, int addr_len, unsigned char addr_type, bool global, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev_addr_lists.c (0)
Location: net/core/dev_addr_lists.c:51
Inline: False
Direct callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
**Symbols:**

```
ffffffff81dd1de0-ffffffff81dd1ed8: __hw_addr_create (STB_LOCAL)
ffffffff820aba43-ffffffff820aba66: __hw_addr_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct netdev_hw_addr *__hw_addr_create(const unsigned char *addr, int addr_len, unsigned char addr_type, bool global, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev_addr_lists.c (0)
Location: net/core/dev_addr_lists.c:51
Inline: False
Direct callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
**Symbols:**

```
ffffffff81e429b0-ffffffff81e42aa8: __hw_addr_create (STB_LOCAL)
ffffffff8212d180-ffffffff8212d1a3: __hw_addr_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct netdev_hw_addr *__hw_addr_create(const unsigned char *addr, int addr_len, unsigned char addr_type, bool global, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev_addr_lists.c (0)
Location: net/core/dev_addr_lists.c:51
Inline: False
Direct callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
**Symbols:**

```
ffffffff81f015d0-ffffffff81f016f7: __hw_addr_create (STB_LOCAL)
ffffffff8220eeac-ffffffff8220eecf: __hw_addr_create.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
