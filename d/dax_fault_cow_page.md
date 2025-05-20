# Function: <code>dax_fault_cow_page</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t dax_fault_cow_page(struct vm_fault *vmf, const struct iomap_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f4c40)
Location: fs/dax.c:1332
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff813f4c40-ffffffff813f4dd6: dax_fault_cow_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t dax_fault_cow_page(struct vm_fault *vmf, const struct iomap_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81467840)
Location: fs/dax.c:1295
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff81467840-ffffffff814679c9: dax_fault_cow_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t dax_fault_cow_page(struct vm_fault *vmf, const struct iomap_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f7f00)
Location: fs/dax.c:1574
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff814f7f00-ffffffff814f8089: dax_fault_cow_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t dax_fault_cow_page(struct vm_fault *vmf, const struct iomap_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8152f100)
Location: fs/dax.c:1617
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff8152f100-ffffffff8152f29a: dax_fault_cow_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t dax_fault_cow_page(struct vm_fault *vmf, const struct iomap_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81563fe0)
Location: fs/dax.c:1603
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff81563fe0-ffffffff8156417a: dax_fault_cow_page (STB_LOCAL)
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
