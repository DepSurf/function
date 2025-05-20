# Function: <code>acpi_ut_walk_package_tree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff814a895c)
Location: drivers/acpi/acpica/utmisc.c:232
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff814a895c-ffffffff814a8a7b: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff814f7c1f)
Location: drivers/acpi/acpica/utmisc.c:232
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff814f7c1f-ffffffff814f7d4a: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff8151a83b)
Location: drivers/acpi/acpica/utmisc.c:232
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff8151a83b-ffffffff8151a966: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff8152b064)
Location: drivers/acpi/acpica/utmisc.c:232
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff8152b064-ffffffff8152b189: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff815848b1)
Location: drivers/acpi/acpica/utmisc.c:232
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff815848b1-ffffffff81584aa8: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff815bba22)
Location: drivers/acpi/acpica/utmisc.c:196
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff815bba22-ffffffff815bbc19: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff815d4e74)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff815d4e74-ffffffff815d505f: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff816067f1)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff816067f1-ffffffff816069f8: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff81627c8c)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff81627c8c-ffffffff81627e93: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff816d4426)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ipackage_to_ipackage
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_package_object_size
```
**Symbols:**

```
ffffffff816d4426-ffffffff816d462d: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff816f23f3)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ipackage_to_ipackage
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_package_object_size
```
**Symbols:**

```
ffffffff816f23f3-ffffffff816f25fa: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff816d429e)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff816d429e-ffffffff816d44ab: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff8174bb75)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff8174bb75-ffffffff8174bd82: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff8187e17d)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff8187e17d-ffffffff8187e393: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff819c1d10)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff819c1d10-ffffffff819c1f4c: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff81a09060)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff81a09060-ffffffff81a0929c: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff81a53f70)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff81a53f70-ffffffff81a541ac: acpi_ut_walk_package_tree (STB_GLOBAL)
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
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffff80001079cd84)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffff80001079cd84-ffff80001079cef8: acpi_ut_walk_package_tree (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff815ffdcd)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff815ffdcd-ffffffff815fff18: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff815eb2ba)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff815eb2ba-ffffffff815eb405: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff8161bf6c)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff8161bf6c-ffffffff8161c173: acpi_ut_walk_package_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ut_walk_package_tree(union acpi_operand_object *source_object, void *target_object, acpi_pkg_callback walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmisc.c (ffffffff81635e1c)
Location: drivers/acpi/acpica/utmisc.c:197
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_eobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
```
**Symbols:**

```
ffffffff81635e1c-ffffffff81636023: acpi_ut_walk_package_tree (STB_GLOBAL)
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
