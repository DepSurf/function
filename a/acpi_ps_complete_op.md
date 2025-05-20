# Function: <code>acpi_ps_complete_op</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff814a17de)
Location: drivers/acpi/acpica/psobject.c:388
Inline: True
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff814a17de-ffffffff814a19fb: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff814f0ae3)
Location: drivers/acpi/acpica/psobject.c:388
Inline: True
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff814f0ae3-ffffffff814f0d11: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff81513538)
Location: drivers/acpi/acpica/psobject.c:388
Inline: True
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff81513538-ffffffff81513766: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff81523c99)
Location: drivers/acpi/acpica/psobject.c:448
Inline: True
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff81523c99-ffffffff81523ec7: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff81579049)
Location: drivers/acpi/acpica/psobject.c:474
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff81579049-ffffffff81579452: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff815b00d0)
Location: drivers/acpi/acpica/psobject.c:437
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff815b00d0-ffffffff815b0550: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff815c916d)
Location: drivers/acpi/acpica/psobject.c:437
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff815c916d-ffffffff815c95f4: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff815fa901)
Location: drivers/acpi/acpica/psobject.c:437
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff815fa901-ffffffff815fad8c: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff8161bda8)
Location: drivers/acpi/acpica/psobject.c:437
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff8161bda8-ffffffff8161c233: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff816c8331)
Location: drivers/acpi/acpica/psobject.c:437
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff816c8331-ffffffff816c87bc: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff816e6357)
Location: drivers/acpi/acpica/psobject.c:437
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff816e6357-ffffffff816e67e2: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff816c821b)
Location: drivers/acpi/acpica/psobject.c:437
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff816c821b-ffffffff816c86a3: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff8173f586)
Location: drivers/acpi/acpica/psobject.c:437
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff8173f586-ffffffff8173fa0e: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff81870e2a)
Location: drivers/acpi/acpica/psobject.c:437
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff81870e2a-ffffffff818712b0: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff819b1690)
Location: drivers/acpi/acpica/psobject.c:437
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff819b1690-ffffffff819b1b91: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff819f8590)
Location: drivers/acpi/acpica/psobject.c:437
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff819f8590-ffffffff819f8aa4: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff81a433e0)
Location: drivers/acpi/acpica/psobject.c:437
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff81a433e0-ffffffff81a438f4: acpi_ps_complete_op (STB_GLOBAL)
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
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffff800010792e74)
Location: drivers/acpi/acpica/psobject.c:437
Inline: True
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffff800010792e74-ffff8000107930f8: acpi_ps_complete_op (STB_GLOBAL)
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
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff815f848b)
Location: drivers/acpi/acpica/psobject.c:437
Inline: True
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff815f848b-ffffffff815f870e: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff815e39ca)
Location: drivers/acpi/acpica/psobject.c:437
Inline: True
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff815e39ca-ffffffff815e3c4d: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff81610088)
Location: drivers/acpi/acpica/psobject.c:437
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff81610088-ffffffff81610513: acpi_ps_complete_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ps_complete_op(struct acpi_walk_state *walk_state, union acpi_parse_object **op, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psobject.c (ffffffff81629f38)
Location: drivers/acpi/acpica/psobject.c:437
Inline: False
Direct callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
```
**Symbols:**

```
ffffffff81629f38-ffffffff8162a3c3: acpi_ps_complete_op (STB_GLOBAL)
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
