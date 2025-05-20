# Function: <code>__devlink_port_phys_port_name_get</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81951df9)
Location: net/core/devlink.c:5869
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
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
In net/core/devlink.c (ffffffff81988835)
Location: net/core/devlink.c:6566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __devlink_port_phys_port_name_get(struct devlink_port *devlink_port, char *name, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a51720)
Location: net/core/devlink.c:7502
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
```
**Symbols:**

```
ffffffff81a51720-ffffffff81a517f7: __devlink_port_phys_port_name_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __devlink_port_phys_port_name_get(struct devlink_port *devlink_port, char *name, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a57830)
Location: net/core/devlink.c:8375
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
```
**Symbols:**

```
ffffffff81a57830-ffffffff81a57993: __devlink_port_phys_port_name_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __devlink_port_phys_port_name_get(struct devlink_port *devlink_port, char *name, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3a530)
Location: net/core/devlink.c:8622
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
```
**Symbols:**

```
ffffffff81a3a530-ffffffff81a3a712: __devlink_port_phys_port_name_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __devlink_port_phys_port_name_get(struct devlink_port *devlink_port, char *name, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af03e0)
Location: net/core/devlink.c:9469
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
```
**Symbols:**

```
ffffffff81af03e0-ffffffff81af05c3: __devlink_port_phys_port_name_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __devlink_port_phys_port_name_get(struct devlink_port *devlink_port, char *name, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c739c0)
Location: net/core/devlink.c:10127
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
```
**Symbols:**

```
ffffffff81c739c0-ffffffff81c73c26: __devlink_port_phys_port_name_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __devlink_port_phys_port_name_get(struct devlink_port *devlink_port, char *name, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2c5b0)
Location: net/core/devlink.c:10815
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
```
**Symbols:**

```
ffffffff81e2c5b0-ffffffff81e2c816: __devlink_port_phys_port_name_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __devlink_port_phys_port_name_get(struct devlink_port *devlink_port, char *name, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82030160)
Location: net/devlink/leftover.c:7383
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_compat_phys_port_name_get
```
**Symbols:**

```
ffffffff82030160-ffffffff820303b1: __devlink_port_phys_port_name_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __devlink_port_phys_port_name_get(struct devlink_port *devlink_port, char *name, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/port.c (ffffffff82105fc0)
Location: net/devlink/port.c:1462
Inline: False
Direct callers:
  - net/devlink/port.c:devlink_compat_phys_port_name_get
```
**Symbols:**

```
ffffffff82105fc0-ffffffff82106215: __devlink_port_phys_port_name_get (STB_LOCAL)
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
In net/core/devlink.c (ffff800010c307bc)
Location: net/core/devlink.c:6566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
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
In net/core/devlink.c (c0d477bc)
Location: net/core/devlink.c:6566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
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
In net/core/devlink.c (c000000000d296a0)
Location: net/core/devlink.c:6566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
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
In net/core/devlink.c (ffffffe0007a694a)
Location: net/core/devlink.c:6566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
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
In net/core/devlink.c (ffffffff819286a5)
Location: net/core/devlink.c:6566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
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
In net/core/devlink.c (ffffffff818e2455)
Location: net/core/devlink.c:6566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
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
In net/core/devlink.c (ffffffff81979835)
Location: net/core/devlink.c:6566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
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
In net/core/devlink.c (ffffffff8199bd25)
Location: net/core/devlink.c:6566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_phys_port_name_get
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
