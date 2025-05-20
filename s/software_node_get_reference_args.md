# Function: <code>software_node_get_reference_args</code>

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
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e3e10)
Location: drivers/base/swnode.c:564
Inline: False
```
**Symbols:**

```
ffffffff816e3e10-ffffffff816e3f67: software_node_get_reference_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81708770)
Location: drivers/base/swnode.c:567
Inline: False
```
**Symbols:**

```
ffffffff81708770-ffffffff817088c7: software_node_get_reference_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c3690)
Location: drivers/base/swnode.c:476
Inline: False
```
**Symbols:**

```
ffffffff817c3690-ffffffff817c3850: software_node_get_reference_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d8630)
Location: drivers/base/swnode.c:480
Inline: False
```
**Symbols:**

```
ffffffff817d8630-ffffffff817d87f0: software_node_get_reference_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bc400)
Location: drivers/base/swnode.c:494
Inline: False
```
**Symbols:**

```
ffffffff817bc400-ffffffff817bc5be: software_node_get_reference_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:496
Inline: False
```
**Symbols:**

```
ffffffff81846750-ffffffff8184690c: software_node_get_reference_args (STB_LOCAL)
ffffffff81d034a0-ffffffff81d034b4: software_node_get_reference_args.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:493
Inline: False
```
**Symbols:**

```
ffffffff8198ae80-ffffffff8198b0d4: software_node_get_reference_args (STB_LOCAL)
ffffffff81ecbc07-ffffffff81ecbc1b: software_node_get_reference_args.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:493
Inline: False
```
**Symbols:**

```
ffffffff81afa360-ffffffff81afa5b4: software_node_get_reference_args (STB_LOCAL)
ffffffff8209886f-ffffffff82098883: software_node_get_reference_args.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:493
Inline: False
```
**Symbols:**

```
ffffffff81b486f0-ffffffff81b489a5: software_node_get_reference_args (STB_LOCAL)
ffffffff82119881-ffffffff8211989c: software_node_get_reference_args.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:493
Inline: False
```
**Symbols:**

```
ffffffff81ba0ae0-ffffffff81ba0d93: software_node_get_reference_args (STB_LOCAL)
ffffffff821f7843-ffffffff821f785e: software_node_get_reference_args.cold (STB_LOCAL)
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
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f6008)
Location: drivers/base/swnode.c:567
Inline: False
```
**Symbols:**

```
ffff8000108f6008-ffff8000108f6174: software_node_get_reference_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e1ee0)
Location: drivers/base/swnode.c:567
Inline: False
```
**Symbols:**

```
c09e1ee0-c09e2044: software_node_get_reference_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c000000000990ef0)
Location: drivers/base/swnode.c:567
Inline: False
```
**Symbols:**

```
c000000000990ef0-c0000000009912c0: software_node_get_reference_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe000587030)
Location: drivers/base/swnode.c:567
Inline: False
```
**Symbols:**

```
ffffffe000587030-ffffffe00058715a: software_node_get_reference_args (STB_LOCAL)
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
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cdec0)
Location: drivers/base/swnode.c:567
Inline: False
```
**Symbols:**

```
ffffffff816cdec0-ffffffff816ce017: software_node_get_reference_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a91f0)
Location: drivers/base/swnode.c:567
Inline: False
```
**Symbols:**

```
ffffffff816a91f0-ffffffff816a9347: software_node_get_reference_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fc430)
Location: drivers/base/swnode.c:567
Inline: False
```
**Symbols:**

```
ffffffff816fc430-ffffffff816fc587: software_node_get_reference_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int software_node_get_reference_args(const struct fwnode_handle *fwnode, const char *propname, const char *nargs_prop, unsigned int nargs, unsigned int index, struct fwnode_reference_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81716640)
Location: drivers/base/swnode.c:567
Inline: False
```
**Symbols:**

```
ffffffff81716640-ffffffff81716797: software_node_get_reference_args (STB_LOCAL)
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
