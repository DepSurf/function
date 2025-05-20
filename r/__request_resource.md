# Function: <code>__request_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81085f60)
Location: kernel/resource.c:208
Inline: False
Direct callers:
  - kernel/resource.c:request_resource
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff81085f60-ffffffff81085fce: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81088d80)
Location: kernel/resource.c:217
Inline: False
Direct callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource
```
**Symbols:**

```
ffffffff81088d80-ffffffff81088deb: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108dcd0)
Location: kernel/resource.c:217
Inline: False
Direct callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource
```
**Symbols:**

```
ffffffff8108dcd0-ffffffff8108dd3b: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108ad00)
Location: kernel/resource.c:217
Inline: False
Direct callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource
```
**Symbols:**

```
ffffffff8108ad00-ffffffff8108ad6d: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810919e0)
Location: kernel/resource.c:217
Inline: False
Direct callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource
```
**Symbols:**

```
ffffffff810919e0-ffffffff81091a4d: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810954d0)
Location: kernel/resource.c:184
Inline: False
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource_conflict
```
**Symbols:**

```
ffffffff810954d0-ffffffff8109553d: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109d850)
Location: kernel/resource.c:184
Inline: False
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource_conflict
```
**Symbols:**

```
ffffffff8109d850-ffffffff8109d8bd: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a1e10)
Location: kernel/resource.c:185
Inline: False
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource_conflict
```
**Symbols:**

```
ffffffff810a1e10-ffffffff810a1e6c: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a83d0)
Location: kernel/resource.c:185
Inline: False
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource_conflict
```
**Symbols:**

```
ffffffff810a83d0-ffffffff810a842c: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0d02)
Location: kernel/resource.c:185
Inline: True
Inline callers:
  - kernel/resource.c:__insert_resource
Direct callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__request_region
  - kernel/resource.c:__reserve_region_with_split
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff810afca0-ffffffff810afcfc: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac462)
Location: kernel/resource.c:185
Inline: True
Inline callers:
  - kernel/resource.c:__insert_resource
Direct callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__request_region
  - kernel/resource.c:__reserve_region_with_split
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff810ab3e0-ffffffff810ab43c: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad692)
Location: kernel/resource.c:184
Inline: True
Inline callers:
  - kernel/resource.c:__insert_resource
Direct callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__request_region_locked
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff810ac560-ffffffff810ac5bc: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bf212)
Location: kernel/resource.c:184
Inline: True
Inline callers:
  - kernel/resource.c:__insert_resource
Direct callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__request_region_locked
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff810be0e0-ffffffff810be13c: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d6517)
Location: kernel/resource.c:171
Inline: True
Inline callers:
  - kernel/resource.c:__insert_resource
Direct callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__request_region_locked
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff810d5120-ffffffff810d519a: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f5597)
Location: kernel/resource.c:171
Inline: True
Inline callers:
  - kernel/resource.c:__insert_resource
Direct callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__request_region_locked
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff810f41b0-ffffffff810f422a: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff811019e2)
Location: kernel/resource.c:171
Inline: True
Inline callers:
  - kernel/resource.c:__insert_resource
Direct callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__request_region_locked
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff811005e0-ffffffff8110065a: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110b132)
Location: kernel/resource.c:171
Inline: True
Inline callers:
  - kernel/resource.c:__insert_resource
Direct callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__request_region_locked
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff81109da0-ffffffff81109e1a: __request_resource (STB_LOCAL)
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
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff8000100ff9b8)
Location: kernel/resource.c:185
Inline: False
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource_conflict
```
**Symbols:**

```
ffff8000100ff9b8-ffff8000100ffa54: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035c504)
Location: kernel/resource.c:185
Inline: False
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:request_resource_conflict
```
**Symbols:**

```
c035c504-c035c594: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000146d20)
Location: kernel/resource.c:185
Inline: False
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource_conflict
```
**Symbols:**

```
c000000000146d20-c000000000146da4: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c753a)
Location: kernel/resource.c:185
Inline: False
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource_conflict
```
**Symbols:**

```
ffffffe0000c753a-ffffffe0000c75a8: __request_resource (STB_LOCAL)
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
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a1cf0)
Location: kernel/resource.c:185
Inline: False
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource_conflict
```
**Symbols:**

```
ffffffff810a1cf0-ffffffff810a1d4c: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810906d0)
Location: kernel/resource.c:185
Inline: False
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource_conflict
```
**Symbols:**

```
ffffffff810906d0-ffffffff8109072c: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a1ca0)
Location: kernel/resource.c:185
Inline: False
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource_conflict
```
**Symbols:**

```
ffffffff810a1ca0-ffffffff810a1cfc: __request_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct resource *__request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a9cc0)
Location: kernel/resource.c:185
Inline: False
Direct callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:__insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:request_resource_conflict
```
**Symbols:**

```
ffffffff810a9cc0-ffffffff810a9d1c: __request_resource (STB_LOCAL)
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
