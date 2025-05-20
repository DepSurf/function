# Function: <code>__acpi_dev_get_resources</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815425c0)
Location: drivers/acpi/resource.c:577
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
```
**Symbols:**

```
ffffffff815425c0-ffffffff8154269c: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81578520)
Location: drivers/acpi/resource.c:577
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
```
**Symbols:**

```
ffffffff81578520-ffffffff815785fb: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81590190)
Location: drivers/acpi/resource.c:577
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
```
**Symbols:**

```
ffffffff81590190-ffffffff8159026b: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815c0f70)
Location: drivers/acpi/resource.c:569
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
```
**Symbols:**

```
ffffffff815c0f70-ffffffff815c104f: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815e2230)
Location: drivers/acpi/resource.c:569
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
```
**Symbols:**

```
ffffffff815e2230-ffffffff815e230f: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168d5af)
Location: drivers/acpi/resource.c:569
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_consumes_res
```
**Symbols:**

```
ffffffff8168cc80-ffffffff8168cd5f: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff816ab2af)
Location: drivers/acpi/resource.c:562
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_consumes_res
```
**Symbols:**

```
ffffffff816aa980-ffffffff816aaa5f: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168db0f)
Location: drivers/acpi/resource.c:607
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
**Symbols:**

```
ffffffff8168d270-ffffffff8168d34f: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8170325f)
Location: drivers/acpi/resource.c:614
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
**Symbols:**

```
ffffffff81702aa0-ffffffff81702b7f: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8183132f)
Location: drivers/acpi/resource.c:614
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
**Symbols:**

```
ffffffff81830980-ffffffff81830a8b: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819648ef)
Location: drivers/acpi/resource.c:731
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
**Symbols:**

```
ffffffff81963af0-ffffffff81963bfb: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819aadaf)
Location: drivers/acpi/resource.c:772
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
**Symbols:**

```
ffffffff819a9f90-ffffffff819aa09b: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819f507f)
Location: drivers/acpi/resource.c:835
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
**Symbols:**

```
ffffffff819f4220-ffffffff819f432b: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffff80001076eb98)
Location: drivers/acpi/resource.c:569
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
```
**Symbols:**

```
ffff80001076eb98-ffff80001076ec80: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815d44f0)
Location: drivers/acpi/resource.c:569
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
```
**Symbols:**

```
ffffffff815d44f0-ffffffff815d45cf: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815be0b0)
Location: drivers/acpi/resource.c:569
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
```
**Symbols:**

```
ffffffff815be0b0-ffffffff815be18f: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815d6510)
Location: drivers/acpi/resource.c:569
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
```
**Symbols:**

```
ffffffff815d6510-ffffffff815d65ef: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data, char *method);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815f03d0)
Location: drivers/acpi/resource.c:569
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
```
**Symbols:**

```
ffffffff815f03d0-ffffffff815f04af: __acpi_dev_get_resources (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
