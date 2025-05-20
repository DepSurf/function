# Function: <code>netlbl_domhsh_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8180cca0)
Location: net/netlabel/netlabel_domainhash.c:636
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff8180cca0-ffffffff8180ccd8: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8187f000)
Location: net/netlabel/netlabel_domainhash.c:807
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff8187f000-ffffffff8187f0b3: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff818b38b0)
Location: net/netlabel/netlabel_domainhash.c:807
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff818b38b0-ffffffff818b3963: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff818da260)
Location: net/netlabel/netlabel_domainhash.c:807
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff818da260-ffffffff818da310: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8195fe50)
Location: net/netlabel/netlabel_domainhash.c:807
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff8195fe50-ffffffff8195ff00: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819b9610)
Location: net/netlabel/netlabel_domainhash.c:807
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff819b9610-ffffffff819b96c3: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819f08e0)
Location: net/netlabel/netlabel_domainhash.c:807
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff819f08e0-ffffffff819f0993: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a5fb90)
Location: net/netlabel/netlabel_domainhash.c:793
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff81a5fb90-ffffffff81a5fc46: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a967c0)
Location: net/netlabel/netlabel_domainhash.c:793
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff81a967c0-ffffffff81a96876: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81b91f25)
Location: net/netlabel/netlabel_domainhash.c:795
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff81b91e50-ffffffff81b91f1c: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81ba1b50)
Location: net/netlabel/netlabel_domainhash.c:794
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff81ba1b50-ffffffff81ba1c15: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81b90c30)
Location: net/netlabel/netlabel_domainhash.c:794
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff81b90c30-ffffffff81b90cf5: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81c5d3d0)
Location: net/netlabel/netlabel_domainhash.c:794
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff81c5d3d0-ffffffff81c5d495: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81dff350)
Location: net/netlabel/netlabel_domainhash.c:794
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff81dff350-ffffffff81dff464: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81fd4020)
Location: net/netlabel/netlabel_domainhash.c:794
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff81fd4020-ffffffff81fd4134: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8204fc70)
Location: net/netlabel/netlabel_domainhash.c:794
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff8204fc70-ffffffff8204fd84: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff82122320)
Location: net/netlabel/netlabel_domainhash.c:794
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff82122320-ffffffff82122434: netlbl_domhsh_remove (STB_GLOBAL)
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
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffff800010d659b8)
Location: net/netlabel/netlabel_domainhash.c:793
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffff800010d659b8-ffff800010d65a94: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (c0e64338)
Location: net/netlabel/netlabel_domainhash.c:793
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
c0e64338-c0e643f0: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (c000000000ea19f0)
Location: net/netlabel/netlabel_domainhash.c:793
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
c000000000ea19f0-c000000000ea1b10: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffe000899622)
Location: net/netlabel/netlabel_domainhash.c:793
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffe000899622-ffffffe0008996c0: netlbl_domhsh_remove (STB_GLOBAL)
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
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a35b50)
Location: net/netlabel/netlabel_domainhash.c:793
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff81a35b50-ffffffff81a35c06: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819f2770)
Location: net/netlabel/netlabel_domainhash.c:793
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff819f2770-ffffffff819f2826: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81aa1a00)
Location: net/netlabel/netlabel_domainhash.c:793
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff81aa1a00-ffffffff81aa1ab6: netlbl_domhsh_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int netlbl_domhsh_remove(const char *domain, u16 family, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81aadd50)
Location: net/netlabel/netlabel_domainhash.c:793
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_map_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
```
**Symbols:**

```
ffffffff81aadd50-ffffffff81aade07: netlbl_domhsh_remove (STB_GLOBAL)
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
<li>
<b>Param reordered. </b>
<code>domain, audit_info</code> ➡️ <code>domain, family, audit_info</code>
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
