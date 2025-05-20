# Function: <code>__insert_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810862f0)
Location: kernel/resource.c:755
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource
  - kernel/resource.c:insert_resource_expand_to_fit
```
**Symbols:**

```
ffffffff810862f0-ffffffff810863fe: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810892e0)
Location: kernel/resource.c:786
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
ffffffff810892e0-ffffffff810893f5: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108e230)
Location: kernel/resource.c:786
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
ffffffff8108e230-ffffffff8108e345: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108b290)
Location: kernel/resource.c:786
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
ffffffff8108b290-ffffffff8108b36e: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091f70)
Location: kernel/resource.c:804
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
ffffffff81091f70-ffffffff8109204e: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81095770)
Location: kernel/resource.c:773
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
```
**Symbols:**

```
ffffffff81095770-ffffffff8109584e: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109daf0)
Location: kernel/resource.c:767
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
```
**Symbols:**

```
ffffffff8109daf0-ffffffff8109dbce: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:781
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
```
**Symbols:**

```
ffffffff810a2260-ffffffff810a2346: __insert_resource (STB_LOCAL)
ffffffff810a393b-ffffffff810a3951: __insert_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a8820)
Location: kernel/resource.c:781
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
```
**Symbols:**

```
ffffffff810a8820-ffffffff810a8913: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0ca0)
Location: kernel/resource.c:781
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
ffffffff810b0ca0-ffffffff810b0db7: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac400)
Location: kernel/resource.c:788
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
ffffffff810ac400-ffffffff810ac517: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad630)
Location: kernel/resource.c:780
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
ffffffff810ad630-ffffffff810ad732: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bf1b0)
Location: kernel/resource.c:780
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
ffffffff810bf1b0-ffffffff810bf2b2: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d64c0)
Location: kernel/resource.c:767
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
ffffffff810d64c0-ffffffff810d661e: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f5540)
Location: kernel/resource.c:768
Inline: False
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
ffffffff810f5540-ffffffff810f569e: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81101980)
Location: kernel/resource.c:768
Inline: False
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
ffffffff81101980-ffffffff81101adc: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110b0d0)
Location: kernel/resource.c:823
Inline: False
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:insert_resource
```
**Symbols:**

```
ffffffff8110b0d0-ffffffff8110b22c: __insert_resource (STB_LOCAL)
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
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff8000100ffc38)
Location: kernel/resource.c:781
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
```
**Symbols:**

```
ffff8000100ffc38-ffff8000100ffd58: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035c970)
Location: kernel/resource.c:781
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
```
**Symbols:**

```
c035c970-c035ca9c: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000147350)
Location: kernel/resource.c:781
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
```
**Symbols:**

```
c000000000147350-c0000000001474f8: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c7950)
Location: kernel/resource.c:781
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
```
**Symbols:**

```
ffffffe0000c7950-ffffffe0000c7a20: __insert_resource (STB_LOCAL)
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
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2140)
Location: kernel/resource.c:781
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
```
**Symbols:**

```
ffffffff810a2140-ffffffff810a2233: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81090b20)
Location: kernel/resource.c:781
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
```
**Symbols:**

```
ffffffff81090b20-ffffffff81090c13: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a20f0)
Location: kernel/resource.c:781
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
```
**Symbols:**

```
ffffffff810a20f0-ffffffff810a21e3: __insert_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct resource *__insert_resource(struct resource *parent, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aa150)
Location: kernel/resource.c:781
Inline: False
Direct callers:
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
```
**Symbols:**

```
ffffffff810aa150-ffffffff810aa243: __insert_resource (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
