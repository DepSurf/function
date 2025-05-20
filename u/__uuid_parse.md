# Function: <code>__uuid_parse</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __uuid_parse(const char *uuid, __u8 *b, const u8 *ei);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81464380)
Location: lib/uuid.c:103
Inline: True
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff81464380-ffffffff814643fe: __uuid_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __uuid_parse(const char *uuid, __u8 *b, const u8 *ei);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81490300)
Location: lib/uuid.c:103
Inline: True
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff81490300-ffffffff8149037e: __uuid_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff814c5190)
Location: lib/uuid.c:103
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff814c50f0-ffffffff814c515f: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff814d9890)
Location: lib/uuid.c:103
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff814d97f0-ffffffff814d985f: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff81505600)
Location: lib/uuid.c:95
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff81505550-ffffffff815055bf: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff815235e0)
Location: lib/uuid.c:95
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff81523530-ffffffff8152359f: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff81586ba0)
Location: lib/uuid.c:105
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff81586ab0-ffffffff81586b23: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff815a3e94)
Location: lib/uuid.c:105
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff815a3da0-ffffffff815a3e13: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff815aada4)
Location: lib/uuid.c:105
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff815aacb0-ffffffff815aad27: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff81614084)
Location: lib/uuid.c:105
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff81613f60-ffffffff81614009: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff816e0967)
Location: lib/uuid.c:105
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff816e0810-ffffffff816e08c4: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff817d0d0d)
Location: lib/uuid.c:105
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff817d0b90-ffffffff817d0c44: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff8180f96d)
Location: lib/uuid.c:105
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff8180f7f0-ffffffff8180f8a4: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff818555ed)
Location: lib/uuid.c:105
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff81855470-ffffffff81855524: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffff80001062d418)
Location: lib/uuid.c:95
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffff80001062d340-ffff80001062d3cc: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (c07d3f58)
Location: lib/uuid.c:95
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
c07d3ea8-c07d3f0c: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (c0000000007d04ec)
Location: lib/uuid.c:95
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
c0000000007d0380-c0000000007d044c: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffe00045d2a2)
Location: lib/uuid.c:95
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffe00045d1e6-ffffffe00045d264: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff8151bbc0)
Location: lib/uuid.c:95
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff8151bb10-ffffffff8151bb7f: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff8150beb0)
Location: lib/uuid.c:95
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff8150be00-ffffffff8150be6f: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff81517c50)
Location: lib/uuid.c:95
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff81517ba0-ffffffff81517c0f: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/uuid.c (ffffffff815313f0)
Location: lib/uuid.c:95
Inline: True
Inline callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
Direct callers:
  - lib/uuid.c:uuid_parse
  - lib/uuid.c:guid_parse
```
**Symbols:**

```
ffffffff81531340-ffffffff815313af: __uuid_parse.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
