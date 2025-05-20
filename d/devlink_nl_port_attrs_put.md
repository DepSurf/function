# Function: <code>devlink_nl_port_attrs_put</code>

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
In net/core/devlink.c (ffffffff8194cc81)
Location: net/core/devlink.c:509
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
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
In net/core/devlink.c (ffffffff819825df)
Location: net/core/devlink.c:506
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_nl_port_attrs_put(struct sk_buff *msg, struct devlink_port *devlink_port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a508b0)
Location: net/core/devlink.c:522
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
**Symbols:**

```
ffffffff81a508b0-ffffffff81a50a22: devlink_nl_port_attrs_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_nl_port_attrs_put(struct sk_buff *msg, struct devlink_port *devlink_port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a56a90)
Location: net/core/devlink.c:660
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
**Symbols:**

```
ffffffff81a56a90-ffffffff81a56cf1: devlink_nl_port_attrs_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_nl_port_attrs_put(struct sk_buff *msg, struct devlink_port *devlink_port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a399f0)
Location: net/core/devlink.c:663
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
**Symbols:**

```
ffffffff81a399f0-ffffffff81a39cc7: devlink_nl_port_attrs_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_nl_port_attrs_put(struct sk_buff *msg, struct devlink_port *devlink_port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81aef710)
Location: net/core/devlink.c:760
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
**Symbols:**

```
ffffffff81aef710-ffffffff81aef9e7: devlink_nl_port_attrs_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_nl_port_attrs_put(struct sk_buff *msg, struct devlink_port *devlink_port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c72c20)
Location: net/core/devlink.c:978
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
**Symbols:**

```
ffffffff81c72c20-ffffffff81c72f0a: devlink_nl_port_attrs_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_nl_port_attrs_put(struct sk_buff *msg, struct devlink_port *devlink_port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2b620)
Location: net/core/devlink.c:1154
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
**Symbols:**

```
ffffffff81e2b620-ffffffff81e2b90a: devlink_nl_port_attrs_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_nl_port_attrs_put(struct sk_buff *msg, struct devlink_port *devlink_port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8202f500)
Location: net/devlink/leftover.c:630
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_port_fill
```
**Symbols:**

```
ffffffff8202f500-ffffffff8202f7ea: devlink_nl_port_attrs_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_nl_port_attrs_put(struct sk_buff *msg, struct devlink_port *devlink_port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/port.c (ffffffff82105550)
Location: net/devlink/port.c:203
Inline: False
Direct callers:
  - net/devlink/port.c:devlink_nl_port_fill
```
**Symbols:**

```
ffffffff82105550-ffffffff8210583a: devlink_nl_port_attrs_put (STB_LOCAL)
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
In net/core/devlink.c (ffff800010c2a6b8)
Location: net/core/devlink.c:506
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
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
In net/core/devlink.c (c0d41b38)
Location: net/core/devlink.c:506
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
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
In net/core/devlink.c (c000000000d1f9c4)
Location: net/core/devlink.c:506
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
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
In net/core/devlink.c (ffffffe0007a1e46)
Location: net/core/devlink.c:506
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
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
In net/core/devlink.c (ffffffff8192244f)
Location: net/core/devlink.c:506
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
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
In net/core/devlink.c (ffffffff818dc1ff)
Location: net/core/devlink.c:506
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
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
In net/core/devlink.c (ffffffff819735df)
Location: net/core/devlink.c:506
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
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
In net/core/devlink.c (ffffffff81995acf)
Location: net/core/devlink.c:506
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
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
