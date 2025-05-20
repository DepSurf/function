# Function: <code>__release_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81086029)
Location: kernel/resource.c:236
Inline: True
Inline callers:
  - kernel/resource.c:release_resource
  - kernel/resource.c:allocate_resource
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81088df0)
Location: kernel/resource.c:245
Inline: False
Direct callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
```
**Symbols:**

```
ffffffff81088df0-ffffffff81088e7c: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108dd40)
Location: kernel/resource.c:245
Inline: False
Direct callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
```
**Symbols:**

```
ffffffff8108dd40-ffffffff8108ddcc: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108ad70)
Location: kernel/resource.c:245
Inline: False
Direct callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
```
**Symbols:**

```
ffffffff8108ad70-ffffffff8108adfa: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091a50)
Location: kernel/resource.c:245
Inline: False
Direct callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
```
**Symbols:**

```
ffffffff81091a50-ffffffff81091ada: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81095540)
Location: kernel/resource.c:212
Inline: False
Direct callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
```
**Symbols:**

```
ffffffff81095540-ffffffff810955cd: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109d8c0)
Location: kernel/resource.c:212
Inline: False
Direct callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
```
**Symbols:**

```
ffffffff8109d8c0-ffffffff8109d94d: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a1e70)
Location: kernel/resource.c:213
Inline: False
Direct callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
```
**Symbols:**

```
ffffffff810a1e70-ffffffff810a1ef5: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a8430)
Location: kernel/resource.c:213
Inline: False
Direct callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
```
**Symbols:**

```
ffffffff810a8430-ffffffff810a84b5: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810afd00)
Location: kernel/resource.c:213
Inline: False
Direct callers:
  - kernel/resource.c:devm_resource_release
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff810afd00-ffffffff810afd85: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ab440)
Location: kernel/resource.c:213
Inline: False
Direct callers:
  - kernel/resource.c:devm_resource_release
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff810ab440-ffffffff810ab4c5: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac5c0)
Location: kernel/resource.c:212
Inline: False
Direct callers:
  - kernel/resource.c:devm_resource_release
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff810ac5c0-ffffffff810ac645: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810be140)
Location: kernel/resource.c:212
Inline: False
Direct callers:
  - kernel/resource.c:devm_resource_release
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff810be140-ffffffff810be1c5: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d51a0)
Location: kernel/resource.c:199
Inline: False
Direct callers:
  - kernel/resource.c:devm_resource_release
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff810d51a0-ffffffff810d523d: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f4240)
Location: kernel/resource.c:199
Inline: False
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:devm_resource_release
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff810f4240-ffffffff810f42dd: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81100670)
Location: kernel/resource.c:199
Inline: False
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:devm_resource_release
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff81100670-ffffffff8110070d: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81109e30)
Location: kernel/resource.c:199
Inline: False
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:devm_resource_release
  - kernel/resource.c:reallocate_resource
```
**Symbols:**

```
ffffffff81109e30-ffffffff81109ecd: __release_resource (STB_LOCAL)
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
In kernel/resource.c (ffff80001010049c)
Location: kernel/resource.c:213
Inline: True
Inline callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
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
In kernel/resource.c (c035cf44)
Location: kernel/resource.c:213
Inline: True
Inline callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:release_resource
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
In kernel/resource.c (c000000000148044)
Location: kernel/resource.c:213
Inline: True
Inline callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
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
In kernel/resource.c (ffffffe0000c7eda)
Location: kernel/resource.c:213
Inline: True
Inline callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
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
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a1d50)
Location: kernel/resource.c:213
Inline: False
Direct callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
```
**Symbols:**

```
ffffffff810a1d50-ffffffff810a1dd5: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81090730)
Location: kernel/resource.c:213
Inline: False
Direct callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
```
**Symbols:**

```
ffffffff81090730-ffffffff810907b5: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a1d00)
Location: kernel/resource.c:213
Inline: False
Direct callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
```
**Symbols:**

```
ffffffff810a1d00-ffffffff810a1d85: __release_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __release_resource(struct resource *old, bool release_child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a9d20)
Location: kernel/resource.c:213
Inline: False
Direct callers:
  - kernel/resource.c:remove_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
```
**Symbols:**

```
ffffffff810a9d20-ffffffff810a9da5: __release_resource (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
