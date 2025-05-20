# Function: <code>netlbl_domhsh_validate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8180c426)
Location: net/netlabel/netlabel_domainhash.c:255
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8187e4d6)
Location: net/netlabel/netlabel_domainhash.c:286
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff818b2d86)
Location: net/netlabel/netlabel_domainhash.c:286
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff818d9736)
Location: net/netlabel/netlabel_domainhash.c:286
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8195f326)
Location: net/netlabel/netlabel_domainhash.c:286
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819b8af5)
Location: net/netlabel/netlabel_domainhash.c:286
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819efdc5)
Location: net/netlabel/netlabel_domainhash.c:286
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a5f595)
Location: net/netlabel/netlabel_domainhash.c:272
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a961c5)
Location: net/netlabel/netlabel_domainhash.c:272
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netlbl_domhsh_validate(const struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81b90e30)
Location: net/netlabel/netlabel_domainhash.c:274
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff81b90e30-ffffffff81b90f8c: netlbl_domhsh_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netlbl_domhsh_validate(const struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81ba0b40)
Location: net/netlabel/netlabel_domainhash.c:274
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff81ba0b40-ffffffff81ba0c9c: netlbl_domhsh_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netlbl_domhsh_validate(const struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81b8fc10)
Location: net/netlabel/netlabel_domainhash.c:274
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff81b8fc10-ffffffff81b8fd6c: netlbl_domhsh_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netlbl_domhsh_validate(const struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81c5c3b0)
Location: net/netlabel/netlabel_domainhash.c:274
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff81c5c3b0-ffffffff81c5c50c: netlbl_domhsh_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netlbl_domhsh_validate(const struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81dfe1c0)
Location: net/netlabel/netlabel_domainhash.c:274
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff81dfe1c0-ffffffff81dfe36e: netlbl_domhsh_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netlbl_domhsh_validate(const struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81fd2dd0)
Location: net/netlabel/netlabel_domainhash.c:274
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff81fd2dd0-ffffffff81fd2f7e: netlbl_domhsh_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netlbl_domhsh_validate(const struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8204ea20)
Location: net/netlabel/netlabel_domainhash.c:274
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff8204ea20-ffffffff8204ebd1: netlbl_domhsh_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netlbl_domhsh_validate(const struct netlbl_dom_map *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff821210a0)
Location: net/netlabel/netlabel_domainhash.c:274
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff821210a0-ffffffff82121251: netlbl_domhsh_validate (STB_LOCAL)
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
In net/netlabel/netlabel_domainhash.c (ffff800010d651ec)
Location: net/netlabel/netlabel_domainhash.c:272
Inline: True
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
In net/netlabel/netlabel_domainhash.c (c0e63c7c)
Location: net/netlabel/netlabel_domainhash.c:272
Inline: True
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
In net/netlabel/netlabel_domainhash.c (c000000000ea10a0)
Location: net/netlabel/netlabel_domainhash.c:272
Inline: True
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
In net/netlabel/netlabel_domainhash.c (ffffffe000898fc6)
Location: net/netlabel/netlabel_domainhash.c:272
Inline: True
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
In net/netlabel/netlabel_domainhash.c (ffffffff81a35555)
Location: net/netlabel/netlabel_domainhash.c:272
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
In net/netlabel/netlabel_domainhash.c (ffffffff819f2175)
Location: net/netlabel/netlabel_domainhash.c:272
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
In net/netlabel/netlabel_domainhash.c (ffffffff81aa1405)
Location: net/netlabel/netlabel_domainhash.c:272
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
In net/netlabel/netlabel_domainhash.c (ffffffff81aad6c5)
Location: net/netlabel/netlabel_domainhash.c:272
Inline: True
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
