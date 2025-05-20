# Function: <code>devlink_port_attrs_set</code>

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
void devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, u32 port_number, bool split, u32 split_subport_number, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819481d0)
Location: net/core/devlink.c:5795
Inline: False
```
**Symbols:**

```
ffffffff819481d0-ffffffff81948222: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, u32 port_number, bool split, u32 split_subport_number, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197d4f0)
Location: net/core/devlink.c:6492
Inline: False
```
**Symbols:**

```
ffffffff8197d4f0-ffffffff8197d542: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, u32 port_number, bool split, u32 split_subport_number, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a518f0)
Location: net/core/devlink.c:7428
Inline: False
```
**Symbols:**

```
ffffffff81a518f0-ffffffff81a51942: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, struct devlink_port_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a569d0)
Location: net/core/devlink.c:8306
Inline: False
```
**Symbols:**

```
ffffffff81a569d0-ffffffff81a56a82: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, struct devlink_port_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a39930)
Location: net/core/devlink.c:8525
Inline: False
```
**Symbols:**

```
ffffffff81a39930-ffffffff81a399eb: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, struct devlink_port_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81aef9f0)
Location: net/core/devlink.c:9268
Inline: False
```
**Symbols:**

```
ffffffff81aef9f0-ffffffff81aefaa3: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, struct devlink_port_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c725b0)
Location: net/core/devlink.c:9875
Inline: False
```
**Symbols:**

```
ffffffff81c725b0-ffffffff81c7268d: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, struct devlink_port_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2cb30)
Location: net/core/devlink.c:10557
Inline: True
```
**Symbols:**

```
ffffffff81e2cb30-ffffffff81e2cc17: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, struct devlink_port_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8202e620)
Location: net/devlink/leftover.c:7125
Inline: False
```
**Symbols:**

```
ffffffff8202e620-ffffffff8202e708: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, struct devlink_port_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/port.c (ffffffff82105890)
Location: net/devlink/port.c:1306
Inline: False
```
**Symbols:**

```
ffffffff82105890-ffffffff82105978: devlink_port_attrs_set (STB_GLOBAL)
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
void devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, u32 port_number, bool split, u32 split_subport_number, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c25010)
Location: net/core/devlink.c:6492
Inline: False
```
**Symbols:**

```
ffff800010c25010-ffff800010c2508c: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, u32 port_number, bool split, u32 split_subport_number, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3c31c)
Location: net/core/devlink.c:6492
Inline: False
```
**Symbols:**

```
c0d3c31c-c0d3c36c: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, u32 port_number, bool split, u32 split_subport_number, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d18cb0)
Location: net/core/devlink.c:6492
Inline: False
```
**Symbols:**

```
c000000000d18cb0-c000000000d18d34: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, u32 port_number, bool split, u32 split_subport_number, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079d534)
Location: net/core/devlink.c:6492
Inline: False
```
**Symbols:**

```
ffffffe00079d534-ffffffe00079d5a8: devlink_port_attrs_set (STB_GLOBAL)
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
void devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, u32 port_number, bool split, u32 split_subport_number, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191d360)
Location: net/core/devlink.c:6492
Inline: False
```
**Symbols:**

```
ffffffff8191d360-ffffffff8191d3b2: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, u32 port_number, bool split, u32 split_subport_number, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d7110)
Location: net/core/devlink.c:6492
Inline: False
```
**Symbols:**

```
ffffffff818d7110-ffffffff818d7162: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, u32 port_number, bool split, u32 split_subport_number, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196e4f0)
Location: net/core/devlink.c:6492
Inline: False
```
**Symbols:**

```
ffffffff8196e4f0-ffffffff8196e542: devlink_port_attrs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, u32 port_number, bool split, u32 split_subport_number, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819909a0)
Location: net/core/devlink.c:6492
Inline: False
```
**Symbols:**

```
ffffffff819909a0-ffffffff819909f2: devlink_port_attrs_set (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct devlink_port_attrs *attrs</code>
</li>
<li>
<b>Param removed. </b>
<code>enum devlink_port_flavour flavour</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 port_number</code>
</li>
<li>
<b>Param removed. </b>
<code>bool split</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 split_subport_number</code>
</li>
<li>
<b>Param removed. </b>
<code>const unsigned char *switch_id</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned char switch_id_len</code>
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
