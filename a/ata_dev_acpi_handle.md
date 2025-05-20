# Function: <code>ata_dev_acpi_handle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff815e11a9)
Location: drivers/ata/libata-acpi.c:59
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
Direct callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_exit
```
**Symbols:**

```
ffffffff815e1850-ffffffff815e1880: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff8163b370)
Location: drivers/ata/libata-acpi.c:59
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff8163b370-ffffffff8163b3a8: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff8166c3f0)
Location: drivers/ata/libata-acpi.c:59
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff8166c3f0-ffffffff8166c428: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff81680a20)
Location: drivers/ata/libata-acpi.c:59
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff81680a20-ffffffff81680a58: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff816ea280)
Location: drivers/ata/libata-acpi.c:59
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff816ea280-ffffffff816ea2b8: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff817274a5)
Location: drivers/ata/libata-acpi.c:59
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff81726ba0-ffffffff81726bcf: ata_dev_acpi_handle.part.7 (STB_LOCAL)
ffffffff81726dd0-ffffffff81726de9: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff81749c85)
Location: drivers/ata/libata-acpi.c:59
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff81749360-ffffffff81749392: ata_dev_acpi_handle.part.7 (STB_LOCAL)
ffffffff817495b0-ffffffff817495c9: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff81785af5)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff817851e0-ffffffff81785213: ata_dev_acpi_handle.part.0 (STB_LOCAL)
ffffffff81785420-ffffffff81785439: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff817a9735)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff817a8e20-ffffffff817a8e53: ata_dev_acpi_handle.part.0 (STB_LOCAL)
ffffffff817a9060-ffffffff817a9079: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff8186f083)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_push_id
  - drivers/ata/libata-acpi.c:ata_acpi_push_id
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff8186e940-ffffffff8186e97e: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff8187dd53)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_push_id
  - drivers/ata/libata-acpi.c:ata_acpi_push_id
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff8187d610-ffffffff8187d64e: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff818604de)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff8185fd80-ffffffff8185fdbe: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff818ef29e)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff818eeb40-ffffffff818eeb7e: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff81a414ae)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff81a40cf0-ffffffff81a40d40: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff81bc771e)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff81bc6f00-ffffffff81bc6f50: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff81c1f2ae)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff81c1eab0-ffffffff81c1eb00: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff81c7440e)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff81c73bb0-ffffffff81c73c00: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-acpi.c (ffff8000109b6388)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffff8000109b5748-ffff8000109b579c: ata_dev_acpi_handle.part.0 (STB_LOCAL)
ffff8000109b5c10-ffff8000109b5c54: ata_dev_acpi_handle (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff8176e765)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
```
**Symbols:**

```
ffffffff8176dee0-ffffffff8176df13: ata_dev_acpi_handle.part.0 (STB_LOCAL)
ffffffff8176e120-ffffffff8176e139: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff8174e5b5)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
```
**Symbols:**

```
ffffffff8174dd30-ffffffff8174dd63: ata_dev_acpi_handle.part.0 (STB_LOCAL)
ffffffff8174df70-ffffffff8174df89: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff8179e5b5)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff8179dca0-ffffffff8179dcd3: ata_dev_acpi_handle.part.0 (STB_LOCAL)
ffffffff8179dee0-ffffffff8179def9: ata_dev_acpi_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_handle ata_dev_acpi_handle(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff817b8435)
Location: drivers/ata/libata-acpi.c:60
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-zpodd.c:zpodd_exit
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff817b7b20-ffffffff817b7b53: ata_dev_acpi_handle.part.0 (STB_LOCAL)
ffffffff817b7d60-ffffffff817b7d79: ata_dev_acpi_handle (STB_GLOBAL)
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
