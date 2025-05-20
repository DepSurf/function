# Function: <code>tomoyo_set_mode</code>

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
In security/tomoyo/common.c (ffffffff8136a4dc)
Location: security/tomoyo/common.c:584
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813a049c)
Location: security/tomoyo/common.c:584
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813b702c)
Location: security/tomoyo/common.c:584
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813cd939)
Location: security/tomoyo/common.c:584
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813f3dd9)
Location: security/tomoyo/common.c:585
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81424d96)
Location: security/tomoyo/common.c:585
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81441406)
Location: security/tomoyo/common.c:585
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8146f015)
Location: security/tomoyo/common.c:594
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81488e15)
Location: security/tomoyo/common.c:594
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_set_mode(char *name, const char *value, struct tomoyo_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814dcb20)
Location: security/tomoyo/common.c:594
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
**Symbols:**

```
ffffffff814dcb20-ffffffff814dcd84: tomoyo_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_set_mode(char *name, const char *value, struct tomoyo_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814f9f40)
Location: security/tomoyo/common.c:594
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
**Symbols:**

```
ffffffff814f9f40-ffffffff814fa1a4: tomoyo_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_set_mode(char *name, const char *value, struct tomoyo_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81500c80)
Location: security/tomoyo/common.c:594
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
**Symbols:**

```
ffffffff81500c80-ffffffff81500ecf: tomoyo_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tomoyo_set_mode(char *name, const char *value, struct tomoyo_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8155bde0)
Location: security/tomoyo/common.c:594
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
**Symbols:**

```
ffffffff8155bde0-ffffffff8155c10c: tomoyo_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tomoyo_set_mode(char *name, const char *value, struct tomoyo_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff815f6e60)
Location: security/tomoyo/common.c:585
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
**Symbols:**

```
ffffffff815f6e60-ffffffff815f7148: tomoyo_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tomoyo_set_mode(char *name, const char *value, struct tomoyo_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff816a7a20)
Location: security/tomoyo/common.c:585
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
**Symbols:**

```
ffffffff816a7a20-ffffffff816a7d08: tomoyo_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tomoyo_set_mode(char *name, const char *value, struct tomoyo_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff816e0420)
Location: security/tomoyo/common.c:585
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
**Symbols:**

```
ffffffff816e0420-ffffffff816e0753: tomoyo_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tomoyo_set_mode(char *name, const char *value, struct tomoyo_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8171d0a0)
Location: security/tomoyo/common.c:586
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
**Symbols:**

```
ffffffff8171d0a0-ffffffff8171d3d3: tomoyo_set_mode (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffff80001057bd24)
Location: security/tomoyo/common.c:594
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
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
In security/tomoyo/common.c (c072c578)
Location: security/tomoyo/common.c:594
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (c0000000006e6ba8)
Location: security/tomoyo/common.c:594
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffe0003cd6c0)
Location: security/tomoyo/common.c:594
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814813f5)
Location: security/tomoyo/common.c:594
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81471e15)
Location: security/tomoyo/common.c:594
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8147d495)
Location: security/tomoyo/common.c:594
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814931e4)
Location: security/tomoyo/common.c:594
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_profile
```
</details>
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
