# Function: <code>acpi_ds_push_walk_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff8148fb2e)
Location: drivers/acpi/acpica/dswstate.c:475
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
Direct callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff8148fb2e-ffffffff8148fb44: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff814de9f1)
Location: drivers/acpi/acpica/dswstate.c:475
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
Direct callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff814de932-ffffffff814de948: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff815012b9)
Location: drivers/acpi/acpica/dswstate.c:475
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
Direct callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff815011fa-ffffffff81501210: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff81511794)
Location: drivers/acpi/acpica/dswstate.c:475
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
Direct callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff815116d5-ffffffff815116eb: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff81558faa)
Location: drivers/acpi/acpica/dswstate.c:475
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff81558faa-ffffffff81559007: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff8158fac5)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff8158fac5-ffffffff8158fb22: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff815a814a)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff815a814a-ffffffff815a81a7: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff815d98aa)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff815d98aa-ffffffff815d9907: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff815fab62)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff815fab62-ffffffff815fabbf: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff816a6c84)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff816a6c84-ffffffff816a6ce1: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff816c447a)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff816c447a-ffffffff816c44d7: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff816a650d)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff816a650d-ffffffff816a656a: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff8171d000)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff8171d000-ffffffff8171d05d: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff8184cfed)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff8184cfed-ffffffff8184d058: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff81986124)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
Direct callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff81985f70-ffffffff81985fdb: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff819ccb54)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
Direct callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff819cc9a0-ffffffff819cca0b: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff81a175fb)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
Direct callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff81a17470-ffffffff81a174db: acpi_ds_push_walk_state (STB_GLOBAL)
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
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffff800010781a64)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
Direct callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffff800010781978-ffff8000107819ac: acpi_ds_push_walk_state (STB_GLOBAL)
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
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff815e52d0)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
Direct callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff815e5210-ffffffff815e5226: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff815d0937)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
Direct callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff815d087c-ffffffff815d0892: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff815eee42)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff815eee42-ffffffff815eee9f: acpi_ds_push_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ds_push_walk_state(struct acpi_walk_state *walk_state, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff81608cf2)
Location: drivers/acpi/acpica/dswstate.c:441
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
**Symbols:**

```
ffffffff81608cf2-ffffffff81608d4f: acpi_ds_push_walk_state (STB_GLOBAL)
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
