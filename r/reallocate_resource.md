# Function: <code>reallocate_resource</code>

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
In kernel/resource.c (ffffffff810873ff)
Location: kernel/resource.c:642
Inline: True
Inline callers:
  - kernel/resource.c:allocate_resource
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108a290)
Location: kernel/resource.c:673
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff8108a290-ffffffff8108a432: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108f1e0)
Location: kernel/resource.c:673
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff8108f1e0-ffffffff8108f382: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108c180)
Location: kernel/resource.c:673
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff8108c180-ffffffff8108c323: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81092ec0)
Location: kernel/resource.c:691
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff81092ec0-ffffffff81093063: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810968f0)
Location: kernel/resource.c:660
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff810968f0-ffffffff81096aa0: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109ec00)
Location: kernel/resource.c:654
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff8109ec00-ffffffff8109edb4: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a3220)
Location: kernel/resource.c:668
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff810a3220-ffffffff810a33e2: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a9850)
Location: kernel/resource.c:668
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff810a9850-ffffffff810a9a12: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b1410)
Location: kernel/resource.c:668
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff810b1410-ffffffff810b15d5: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810acb70)
Location: kernel/resource.c:675
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff810acb70-ffffffff810acd35: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810add60)
Location: kernel/resource.c:667
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff810add60-ffffffff810adf12: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bf8e0)
Location: kernel/resource.c:667
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff810bf8e0-ffffffff810bfa92: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d6d60)
Location: kernel/resource.c:654
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff810d6d60-ffffffff810d6f26: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f67b0)
Location: kernel/resource.c:655
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff810f67b0-ffffffff810f6976: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81102bd0)
Location: kernel/resource.c:655
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff81102bd0-ffffffff81102d85: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110c500)
Location: kernel/resource.c:710
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff8110c500-ffffffff8110c6b5: reallocate_resource (STB_LOCAL)
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
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010101640)
Location: kernel/resource.c:668
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffff800010101640-ffff80001010185c: reallocate_resource (STB_LOCAL)
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
In kernel/resource.c (c035dcc4)
Location: kernel/resource.c:668
Inline: True
Inline callers:
  - kernel/resource.c:allocate_resource
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000148e50)
Location: kernel/resource.c:668
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
c000000000148e50-c0000000001490a4: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c892a)
Location: kernel/resource.c:668
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffe0000c892a-ffffffe0000c8a88: reallocate_resource (STB_LOCAL)
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
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a3170)
Location: kernel/resource.c:668
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff810a3170-ffffffff810a3332: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091b50)
Location: kernel/resource.c:668
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff81091b50-ffffffff81091d12: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a3120)
Location: kernel/resource.c:668
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff810a3120-ffffffff810a32e2: reallocate_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int reallocate_resource(struct resource *root, struct resource *old, resource_size_t newsize, struct resource_constraint *constraint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ab1c0)
Location: kernel/resource.c:668
Inline: False
Direct callers:
  - kernel/resource.c:allocate_resource
```
**Symbols:**

```
ffffffff810ab1c0-ffffffff810ab387: reallocate_resource (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
