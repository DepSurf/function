# Function: <code>netlbl_domhsh_search_def</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8180c3e0)
Location: net/netlabel/netlabel_domainhash.c:170
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
```
**Symbols:**

```
ffffffff8180c3e0-ffffffff8180c405: netlbl_domhsh_search_def.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8187e450)
Location: net/netlabel/netlabel_domainhash.c:184
Inline: True
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
**Symbols:**

```
ffffffff8187e450-ffffffff8187e4b7: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff818b2d00)
Location: net/netlabel/netlabel_domainhash.c:184
Inline: True
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
**Symbols:**

```
ffffffff818b2d00-ffffffff818b2d67: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff818d96b0)
Location: net/netlabel/netlabel_domainhash.c:184
Inline: True
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
ffffffff818d96b0-ffffffff818d9713: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8195f2a0)
Location: net/netlabel/netlabel_domainhash.c:184
Inline: True
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
ffffffff8195f2a0-ffffffff8195f303: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819b8a60)
Location: net/netlabel/netlabel_domainhash.c:184
Inline: True
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
ffffffff819b8a60-ffffffff819b8ac3: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819efd30)
Location: net/netlabel/netlabel_domainhash.c:184
Inline: True
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
ffffffff819efd30-ffffffff819efd93: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a5efa0)
Location: net/netlabel/netlabel_domainhash.c:170
Inline: True
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
ffffffff81a5efa0-ffffffff81a5f003: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a95bd0)
Location: net/netlabel/netlabel_domainhash.c:170
Inline: True
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
ffffffff81a95bd0-ffffffff81a95c33: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81b920a5)
Location: net/netlabel/netlabel_domainhash.c:172
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81b91350-ffffffff81b913bd: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81ba1d15)
Location: net/netlabel/netlabel_domainhash.c:172
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81ba1060-ffffffff81ba10cd: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81b90df5)
Location: net/netlabel/netlabel_domainhash.c:172
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81b90130-ffffffff81b9019d: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81c5d595)
Location: net/netlabel/netlabel_domainhash.c:172
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81c5c8d0-ffffffff81c5c93d: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81dff5a5)
Location: net/netlabel/netlabel_domainhash.c:172
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81dfe790-ffffffff81dfe815: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81fd42b5)
Location: net/netlabel/netlabel_domainhash.c:172
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81fd33f0-ffffffff81fd3475: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8204ff05)
Location: net/netlabel/netlabel_domainhash.c:172
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff8204f050-ffffffff8204f0d1: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff821225b5)
Location: net/netlabel/netlabel_domainhash.c:172
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff821216d0-ffffffff82121751: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffff800010d64a80)
Location: net/netlabel/netlabel_domainhash.c:170
Inline: True
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
ffff800010d64a80-ffff800010d64b1c: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (c0e6356c)
Location: net/netlabel/netlabel_domainhash.c:170
Inline: True
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
c0e6356c-c0e63600: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (c000000000ea1c40)
Location: net/netlabel/netlabel_domainhash.c:170
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
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
c000000000ea0820-c000000000ea0854: netlbl_domhsh_search_def.part.0 (STB_LOCAL)
c000000000ea0860-c000000000ea0924: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffe0008997ac)
Location: net/netlabel/netlabel_domainhash.c:170
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
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
ffffffe000898a1c-ffffffe000898a4c: netlbl_domhsh_search_def.part.0 (STB_LOCAL)
ffffffe000898a4c-ffffffe000898ac8: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a34f60)
Location: net/netlabel/netlabel_domainhash.c:170
Inline: True
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
ffffffff81a34f60-ffffffff81a34fc3: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819f1b80)
Location: net/netlabel/netlabel_domainhash.c:170
Inline: True
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
ffffffff819f1b80-ffffffff819f1be3: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81aa0e10)
Location: net/netlabel/netlabel_domainhash.c:170
Inline: True
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
ffffffff81aa0e10-ffffffff81aa0e73: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct netlbl_dom_map *netlbl_domhsh_search_def(const char *domain, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81aad0f0)
Location: net/netlabel/netlabel_domainhash.c:170
Inline: True
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
ffffffff81aad0f0-ffffffff81aad153: netlbl_domhsh_search_def (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
