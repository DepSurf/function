# Function: <code>__component_match_add</code>

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
void __component_match_add(struct device *master, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff816d4ab0)
Location: drivers/base/component.c:336
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff816d4ab0-ffffffff816d4bf3: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __component_match_add(struct device *master, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff816f8980)
Location: drivers/base/component.c:336
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff816f8980-ffffffff816f8ac3: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __component_match_add(struct device *master, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817b1380)
Location: drivers/base/component.c:336
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff817b1380-ffffffff817b14c3: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __component_match_add(struct device *master, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817c5cd0)
Location: drivers/base/component.c:336
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff817c5cd0-ffffffff817c5e13: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __component_match_add(struct device *master, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817a8dc0)
Location: drivers/base/component.c:333
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff817a8dc0-ffffffff817a8f03: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __component_match_add(struct device *master, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81831fa0)
Location: drivers/base/component.c:328
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff81831fa0-ffffffff818320ea: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __component_match_add(struct device *parent, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81973610)
Location: drivers/base/component.c:381
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff81973610-ffffffff81973778: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __component_match_add(struct device *parent, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81adeac0)
Location: drivers/base/component.c:381
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff81adeac0-ffffffff81adec28: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __component_match_add(struct device *parent, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81b2cd40)
Location: drivers/base/component.c:381
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff81b2cd40-ffffffff81b2cea8: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __component_match_add(struct device *parent, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81b844e0)
Location: drivers/base/component.c:381
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff81b844e0-ffffffff81b84648: __component_match_add (STB_LOCAL)
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
void __component_match_add(struct device *master, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffff8000108e2748)
Location: drivers/base/component.c:336
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffff8000108e2748-ffff8000108e2874: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __component_match_add(struct device *master, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (c09d1440)
Location: drivers/base/component.c:336
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
c09d1440-c09d1554: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __component_match_add(struct device *master, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (c0000000009772d0)
Location: drivers/base/component.c:336
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
c0000000009772d0-c0000000009774b0: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __component_match_add(struct device *master, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffe000577d58)
Location: drivers/base/component.c:336
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffe000577d58-ffffffe000577e5c: __component_match_add (STB_LOCAL)
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
void __component_match_add(struct device *master, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff816be170)
Location: drivers/base/component.c:336
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff816be170-ffffffff816be2b3: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __component_match_add(struct device *master, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81699420)
Location: drivers/base/component.c:336
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff81699420-ffffffff81699563: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __component_match_add(struct device *master, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff816ec640)
Location: drivers/base/component.c:336
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff816ec640-ffffffff816ec783: __component_match_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __component_match_add(struct device *master, struct component_match **matchptr, void (*release)(struct device *, void *), int (*compare)(struct device *, void *), int (*compare_typed)(struct device *, int, void *), void *compare_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81706e80)
Location: drivers/base/component.c:336
Inline: False
Direct callers:
  - drivers/base/component.c:component_match_add_typed
  - drivers/base/component.c:component_match_add_release
```
**Symbols:**

```
ffffffff81706e80-ffffffff81706fc3: __component_match_add (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *parent</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *master</code>
</li>
</ul>
</details>
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
