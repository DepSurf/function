# Function: <code>sgx_encl_release</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sgx_encl_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065cd0)
Location: arch/x86/kernel/cpu/sgx/encl.c:399
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81065cd0-ffffffff81065e82: sgx_encl_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sgx_encl_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81067000)
Location: arch/x86/kernel/cpu/sgx/encl.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81067000-ffffffff810671b2: sgx_encl_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sgx_encl_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81071340)
Location: arch/x86/kernel/cpu/sgx/encl.c:432
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81071340-ffffffff810714f7: sgx_encl_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sgx_encl_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107f2a0)
Location: arch/x86/kernel/cpu/sgx/encl.c:533
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff8107f2a0-ffffffff8107f465: sgx_encl_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sgx_encl_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090fc0)
Location: arch/x86/kernel/cpu/sgx/encl.c:680
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81090fc0-ffffffff810912b9: sgx_encl_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sgx_encl_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093f00)
Location: arch/x86/kernel/cpu/sgx/encl.c:680
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81093f00-ffffffff810941f7: sgx_encl_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sgx_encl_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109b3e0)
Location: arch/x86/kernel/cpu/sgx/encl.c:700
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff8109b3e0-ffffffff8109b6d7: sgx_encl_release (STB_GLOBAL)
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
