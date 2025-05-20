# Function: <code>devlink_compat_phys_port_name_get</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6921
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffff81952696-ffffffff819526ae: devlink_compat_phys_port_name_get.cold (STB_LOCAL)
ffffffff81951db0-ffffffff81951eea: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819887f0)
Location: net/core/devlink.c:8085
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffff819887f0-ffffffff8198892c: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a604f0)
Location: net/core/devlink.c:9316
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffff81a604f0-ffffffff81a60581: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a68dd0)
Location: net/core/devlink.c:10279
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffff81a68dd0-ffffffff81a68e61: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4c190)
Location: net/core/devlink.c:10543
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffff81a4c190-ffffffff81a4c221: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:11485
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffff81d38adf-ffffffff81d38af3: devlink_compat_phys_port_name_get.cold (STB_LOCAL)
ffffffff81b04640-ffffffff81b046e0: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:12070
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffff81f05338-ffffffff81f0534d: devlink_compat_phys_port_name_get.cold (STB_LOCAL)
ffffffff81c89ea0-ffffffff81c89f45: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:12951
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffff820ad331-ffffffff820ad346: devlink_compat_phys_port_name_get.cold (STB_LOCAL)
ffffffff81e44aa0-ffffffff81e44b2e: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:9476
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffff8213664b-ffffffff82136660: devlink_compat_phys_port_name_get.cold (STB_LOCAL)
ffffffff82041b70-ffffffff82041bfe: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/port.c (0)
Location: net/devlink/port.c:1533
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffff822180b1-ffffffff822180c6: devlink_compat_phys_port_name_get.cold (STB_LOCAL)
ffffffff821082d0-ffffffff8210835e: devlink_compat_phys_port_name_get (STB_GLOBAL)
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
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c30778)
Location: net/core/devlink.c:8085
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffff800010c30778-ffff800010c308ec: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d4776c)
Location: net/core/devlink.c:8085
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
c0d4776c-c0d478f8: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d29630)
Location: net/core/devlink.c:8085
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
c000000000d29630-c000000000d29810: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a6912)
Location: net/core/devlink.c:8085
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffe0007a6912-ffffffe0007a6a44: devlink_compat_phys_port_name_get (STB_GLOBAL)
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
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81928660)
Location: net/core/devlink.c:8085
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffff81928660-ffffffff8192879c: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818e2410)
Location: net/core/devlink.c:8085
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffff818e2410-ffffffff818e254c: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819797f0)
Location: net/core/devlink.c:8085
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffff819797f0-ffffffff8197992c: devlink_compat_phys_port_name_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device *dev, char *name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8199bce0)
Location: net/core/devlink.c:8085
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_phys_port_name
```
**Symbols:**

```
ffffffff8199bce0-ffffffff8199be1c: devlink_compat_phys_port_name_get (STB_GLOBAL)
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
