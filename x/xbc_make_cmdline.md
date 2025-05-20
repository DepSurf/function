# Function: <code>xbc_make_cmdline</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *xbc_make_cmdline(const char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82cc2d1c)
Location: init/main.c:346
Inline: False
```
**Symbols:**

```
ffffffff82cc2d1c-ffffffff82cc2da6: xbc_make_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *xbc_make_cmdline(const char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82faecc2)
Location: init/main.c:358
Inline: False
```
**Symbols:**

```
ffffffff82faecc2-ffffffff82faed59: xbc_make_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *xbc_make_cmdline(const char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff831b8c11)
Location: init/main.c:359
Inline: False
Direct callers:
  - init/main.c:setup_boot_config
  - init/main.c:setup_boot_config
```
**Symbols:**

```
ffffffff831b8c11-ffffffff831b8ca8: xbc_make_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *xbc_make_cmdline(const char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83298db6)
Location: init/main.c:361
Inline: False
Direct callers:
  - init/main.c:setup_boot_config
  - init/main.c:setup_boot_config
```
**Symbols:**

```
ffffffff83298db6-ffffffff83298e58: xbc_make_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *xbc_make_cmdline(const char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83446f56)
Location: init/main.c:365
Inline: False
Direct callers:
  - init/main.c:setup_boot_config
  - init/main.c:setup_boot_config
```
**Symbols:**

```
ffffffff83446f56-ffffffff8344700a: xbc_make_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *xbc_make_cmdline(const char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83e60080)
Location: init/main.c:368
Inline: False
Direct callers:
  - init/main.c:setup_boot_config
  - init/main.c:setup_boot_config
```
**Symbols:**

```
ffffffff83e60080-ffffffff83e6013b: xbc_make_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *xbc_make_cmdline(const char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83680520)
Location: init/main.c:358
Inline: False
Direct callers:
  - init/main.c:setup_boot_config
  - init/main.c:setup_boot_config
```
**Symbols:**

```
ffffffff83680520-ffffffff836805d9: xbc_make_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *xbc_make_cmdline(const char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff838af520)
Location: init/main.c:358
Inline: False
Direct callers:
  - init/main.c:setup_boot_config
  - init/main.c:setup_boot_config
```
**Symbols:**

```
ffffffff838af520-ffffffff838af5d9: xbc_make_cmdline (STB_LOCAL)
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
