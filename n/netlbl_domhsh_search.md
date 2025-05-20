# Function: <code>netlbl_domhsh_search</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8180c250)
Location: net/netlabel/netlabel_domainhash.c:140
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
```
**Symbols:**

```
ffffffff8180c250-ffffffff8180c2c2: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8187e240)
Location: net/netlabel/netlabel_domainhash.c:150
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
**Symbols:**

```
ffffffff8187e240-ffffffff8187e2d8: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff818b2af0)
Location: net/netlabel/netlabel_domainhash.c:150
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
**Symbols:**

```
ffffffff818b2af0-ffffffff818b2b88: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff818d94a0)
Location: net/netlabel/netlabel_domainhash.c:150
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff818d94a0-ffffffff818d952a: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8195f090)
Location: net/netlabel/netlabel_domainhash.c:150
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff8195f090-ffffffff8195f11a: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819b8870)
Location: net/netlabel/netlabel_domainhash.c:150
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff819b8870-ffffffff819b88fa: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819efb40)
Location: net/netlabel/netlabel_domainhash.c:150
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff819efb40-ffffffff819efbca: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a5edb0)
Location: net/netlabel/netlabel_domainhash.c:136
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81a5edb0-ffffffff81a5ee3f: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a959e0)
Location: net/netlabel/netlabel_domainhash.c:136
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81a959e0-ffffffff81a95a6f: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81b91f43)
Location: net/netlabel/netlabel_domainhash.c:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81b91160-ffffffff81b911ef: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81ba1bfe)
Location: net/netlabel/netlabel_domainhash.c:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81ba0e70-ffffffff81ba0eff: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81b90cde)
Location: net/netlabel/netlabel_domainhash.c:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81b8ff40-ffffffff81b8ffcf: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81c5d47e)
Location: net/netlabel/netlabel_domainhash.c:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81c5c6e0-ffffffff81c5c76f: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81dff446)
Location: net/netlabel/netlabel_domainhash.c:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81dfe570-ffffffff81dfe604: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81fd4116)
Location: net/netlabel/netlabel_domainhash.c:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81fd31b0-ffffffff81fd3244: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8204fd66)
Location: net/netlabel/netlabel_domainhash.c:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff8204ee10-ffffffff8204eea4: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff82122416)
Location: net/netlabel/netlabel_domainhash.c:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff82121490-ffffffff82121524: netlbl_domhsh_search (STB_LOCAL)
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
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffff800010d647f0)
Location: net/netlabel/netlabel_domainhash.c:136
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffff800010d647f0-ffff800010d64894: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (c0e63338)
Location: net/netlabel/netlabel_domainhash.c:136
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
c0e63338-c0e633e0: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (c000000000ea1b08)
Location: net/netlabel/netlabel_domainhash.c:136
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
c000000000ea0320-c000000000ea0604: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffe0008996b6)
Location: net/netlabel/netlabel_domainhash.c:136
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffe0008987b6-ffffffe000898846: netlbl_domhsh_search (STB_LOCAL)
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
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a34d70)
Location: net/netlabel/netlabel_domainhash.c:136
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81a34d70-ffffffff81a34dff: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819f1990)
Location: net/netlabel/netlabel_domainhash.c:136
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff819f1990-ffffffff819f1a1f: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81aa0c20)
Location: net/netlabel/netlabel_domainhash.c:136
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81aa0c20-ffffffff81aa0caf: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81aacf00)
Location: net/netlabel/netlabel_domainhash.c:136
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81aacf00-ffffffff81aacf8f: netlbl_domhsh_search (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u16 family</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
