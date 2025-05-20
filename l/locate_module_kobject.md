# Function: <code>locate_module_kobject</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81f7c8de)
Location: kernel/params.c:798
Inline: True
```
**Symbols:**

```
ffffffff81f7c8de-ffffffff81f7c99f: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81fa569a)
Location: kernel/params.c:798
Inline: True
```
**Symbols:**

```
ffffffff81fa569a-ffffffff81fa575b: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81fe119f)
Location: kernel/params.c:798
Inline: True
```
**Symbols:**

```
ffffffff81fe119f-ffffffff81fe1260: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff820c1fb9)
Location: kernel/params.c:746
Inline: True
```
**Symbols:**

```
ffffffff820c1fb9-ffffffff820c2082: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff826ca105)
Location: kernel/params.c:759
Inline: True
```
**Symbols:**

```
ffffffff826ca105-ffffffff826ca1ce: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff826f4351)
Location: kernel/params.c:759
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
```
**Symbols:**

```
ffffffff826f4351-ffffffff826f441a: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff828ab139)
Location: kernel/params.c:759
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
```
**Symbols:**

```
ffffffff828ab139-ffffffff828ab207: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff828c3919)
Location: kernel/params.c:747
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
```
**Symbols:**

```
ffffffff828c3919-ffffffff828c39ea: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff828cbeec)
Location: kernel/params.c:742
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
```
**Symbols:**

```
ffffffff828cbeec-ffffffff828cbfbd: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff82cede95)
Location: kernel/params.c:742
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:kernel_add_sysfs_param
```
**Symbols:**

```
ffffffff82cede95-ffffffff82cedf66: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff82fda4ef)
Location: kernel/params.c:743
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:kernel_add_sysfs_param
```
**Symbols:**

```
ffffffff82fda4ef-ffffffff82fda5c0: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff831e4e8c)
Location: kernel/params.c:743
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_builtin
```
**Symbols:**

```
ffffffff831e4e8c-ffffffff831e4f5d: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff832c8d0c)
Location: kernel/params.c:761
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_builtin
```
**Symbols:**

```
ffffffff832c8d0c-ffffffff832c8ddd: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8347be6e)
Location: kernel/params.c:761
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_builtin
```
**Symbols:**

```
ffffffff8347be6e-ffffffff8347bf49: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff83ea70d0)
Location: kernel/params.c:761
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:param_sysfs_builtin
```
**Symbols:**

```
ffffffff83ea70d0-ffffffff83ea71b1: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff836cba30)
Location: kernel/params.c:762
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:param_sysfs_builtin
```
**Symbols:**

```
ffffffff836cba30-ffffffff836cbb11: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff838fce00)
Location: kernel/params.c:766
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:param_sysfs_builtin
```
**Symbols:**

```
ffffffff838fce00-ffffffff838fcf10: locate_module_kobject (STB_LOCAL)
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
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffff80001144373c)
Location: kernel/params.c:742
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
```
**Symbols:**

```
ffff80001144373c-ffff80001144381c: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (c151d604)
Location: kernel/params.c:742
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
```
**Symbols:**

```
c151d604-c151d6e4: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (c00000000136785c)
Location: kernel/params.c:742
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
```
**Symbols:**

```
c00000000136785c-c000000001367990: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffe0000058b8)
Location: kernel/params.c:742
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
```
**Symbols:**

```
ffffffe0000058b8-ffffffe00000598e: locate_module_kobject (STB_LOCAL)
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
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff828b4cdf)
Location: kernel/params.c:742
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
```
**Symbols:**

```
ffffffff828b4cdf-ffffffff828b4db0: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff828ace60)
Location: kernel/params.c:742
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
```
**Symbols:**

```
ffffffff828ace60-ffffffff828acf31: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff828c7bde)
Location: kernel/params.c:742
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
```
**Symbols:**

```
ffffffff828c7bde-ffffffff828c7caf: locate_module_kobject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct module_kobject *locate_module_kobject(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff828ccf35)
Location: kernel/params.c:742
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
```
**Symbols:**

```
ffffffff828ccf35-ffffffff828cd006: locate_module_kobject (STB_LOCAL)
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
