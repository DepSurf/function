# Function: <code>spi_set_thread_rt</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817926ae)
Location: drivers/spi/spi.c:1435
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff817926ae-ffffffff8179270f: spi_set_thread_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817b6250)
Location: drivers/spi/spi.c:1437
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff817b6250-ffffffff817b62b1: spi_set_thread_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8187d0ed)
Location: drivers/spi/spi.c:1603
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_init_queue
```
**Symbols:**

```
ffffffff8187d0ed-ffffffff8187d14e: spi_set_thread_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c18b50)
Location: drivers/spi/spi.c:1648
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_controller_initialize_queue
```
**Symbols:**

```
ffffffff81c18b50-ffffffff81c18b7c: spi_set_thread_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c0a948)
Location: drivers/spi/spi.c:1660
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81c0a948-ffffffff81c0a974: spi_set_thread_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81d0f808)
Location: drivers/spi/spi.c:1739
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81d0f808-ffffffff81d0f834: spi_set_thread_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81eda50e)
Location: drivers/spi/spi.c:1781
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81eda50e-ffffffff81eda544: spi_set_thread_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd7a1e)
Location: drivers/spi/spi.c:1943
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_controller_initialize_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2e3cf)
Location: drivers/spi/spi.c:1950
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_controller_initialize_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81ce0e1f)
Location: drivers/spi/spi.c:2027
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_controller_initialize_queue
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
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109ca220)
Location: drivers/spi/spi.c:1437
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffff8000109ca220-ffff8000109ca290: spi_set_thread_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0ab36d0)
Location: drivers/spi/spi.c:1437
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
c0ab36d0-c0ab3748: spi_set_thread_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a8b98c)
Location: drivers/spi/spi.c:1437
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
c000000000a8b98c-c000000000a8ba18: spi_set_thread_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000619cc8)
Location: drivers/spi/spi.c:1437
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffe000619cc8-ffffffe000619d14: spi_set_thread_rt (STB_LOCAL)
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
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8177ad30)
Location: drivers/spi/spi.c:1437
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff8177ad30-ffffffff8177ad91: spi_set_thread_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8175aae0)
Location: drivers/spi/spi.c:1437
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff8175aae0-ffffffff8175ab41: spi_set_thread_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817ab0d0)
Location: drivers/spi/spi.c:1437
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff817ab0d0-ffffffff817ab131: spi_set_thread_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void spi_set_thread_rt(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817c5060)
Location: drivers/spi/spi.c:1437
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff817c5060-ffffffff817c50c1: spi_set_thread_rt (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
