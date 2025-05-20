# Function: <code>__request_region_locked</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __request_region_locked(struct resource *res, struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1163
Inline: False
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__request_region
```
**Symbols:**

```
ffffffff810aca60-ffffffff810acbb5: __request_region_locked (STB_LOCAL)
ffffffff81bcd8f1-ffffffff81bcd90c: __request_region_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __request_region_locked(struct resource *res, struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1163
Inline: False
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__request_region
```
**Symbols:**

```
ffffffff810be5e0-ffffffff810be726: __request_region_locked (STB_LOCAL)
ffffffff81ca42d9-ffffffff81ca42f4: __request_region_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __request_region_locked(struct resource *res, struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1150
Inline: False
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__request_region
```
**Symbols:**

```
ffffffff810d5780-ffffffff810d58de: __request_region_locked (STB_LOCAL)
ffffffff81e53b6a-ffffffff81e53b85: __request_region_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __request_region_locked(struct resource *res, struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f4730)
Location: kernel/resource.c:1158
Inline: False
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:__request_region
```
**Symbols:**

```
ffffffff810f4730-ffffffff810f48a5: __request_region_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __request_region_locked(struct resource *res, struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81100b60)
Location: kernel/resource.c:1158
Inline: False
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:__request_region
```
**Symbols:**

```
ffffffff81100b60-ffffffff81100cd5: __request_region_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __request_region_locked(struct resource *res, struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110a490)
Location: kernel/resource.c:1213
Inline: False
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:__request_region
```
**Symbols:**

```
ffffffff8110a490-ffffffff8110a605: __request_region_locked (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
