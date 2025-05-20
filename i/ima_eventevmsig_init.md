# Function: <code>ima_eventevmsig_init</code>

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
int ima_eventevmsig_init(struct ima_event_data *event_data, struct ima_field_data *field_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff815a0b40)
Location: security/integrity/ima/ima_template_lib.c:533
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
```
**Symbols:**

```
ffffffff815a0b40-ffffffff815a0c0c: ima_eventevmsig_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_eventevmsig_init(struct ima_event_data *event_data, struct ima_field_data *field_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff81646a50)
Location: security/integrity/ima/ima_template_lib.c:592
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
```
**Symbols:**

```
ffffffff81646a50-ffffffff81646b2d: ima_eventevmsig_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_eventevmsig_init(struct ima_event_data *event_data, struct ima_field_data *field_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff816ff150)
Location: security/integrity/ima/ima_template_lib.c:592
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
```
**Symbols:**

```
ffffffff816ff150-ffffffff816ff229: ima_eventevmsig_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_eventevmsig_init(struct ima_event_data *event_data, struct ima_field_data *field_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff817391c0)
Location: security/integrity/ima/ima_template_lib.c:592
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
```
**Symbols:**

```
ffffffff817391c0-ffffffff8173929f: ima_eventevmsig_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_eventevmsig_init(struct ima_event_data *event_data, struct ima_field_data *field_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff81779ce0)
Location: security/integrity/ima/ima_template_lib.c:592
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
```
**Symbols:**

```
ffffffff81779ce0-ffffffff81779dbf: ima_eventevmsig_init (STB_GLOBAL)
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
