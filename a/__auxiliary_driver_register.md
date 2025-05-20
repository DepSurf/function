# Function: <code>__auxiliary_driver_register</code>

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
int __auxiliary_driver_register(struct auxiliary_driver *auxdrv, struct module *owner, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff817d8b80)
Location: drivers/base/auxiliary.c:231
Inline: False
```
**Symbols:**

```
ffffffff817d8b80-ffffffff817d8c19: __auxiliary_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __auxiliary_driver_register(struct auxiliary_driver *auxdrv, struct module *owner, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff817bccc0)
Location: drivers/base/auxiliary.c:231
Inline: False
```
**Symbols:**

```
ffffffff817bccc0-ffffffff817bcd83: __auxiliary_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __auxiliary_driver_register(struct auxiliary_driver *auxdrv, struct module *owner, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81847010)
Location: drivers/base/auxiliary.c:229
Inline: False
```
**Symbols:**

```
ffffffff81847010-ffffffff818470d3: __auxiliary_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __auxiliary_driver_register(struct auxiliary_driver *auxdrv, struct module *owner, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff8198ba50)
Location: drivers/base/auxiliary.c:377
Inline: False
```
**Symbols:**

```
ffffffff8198ba50-ffffffff8198bb3b: __auxiliary_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __auxiliary_driver_register(struct auxiliary_driver *auxdrv, struct module *owner, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81afb0e0)
Location: drivers/base/auxiliary.c:377
Inline: False
```
**Symbols:**

```
ffffffff81afb0e0-ffffffff81afb1cb: __auxiliary_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __auxiliary_driver_register(struct auxiliary_driver *auxdrv, struct module *owner, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81b494d0)
Location: drivers/base/auxiliary.c:377
Inline: False
```
**Symbols:**

```
ffffffff81b494d0-ffffffff81b495bb: __auxiliary_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __auxiliary_driver_register(struct auxiliary_driver *auxdrv, struct module *owner, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81ba18c0)
Location: drivers/base/auxiliary.c:377
Inline: False
```
**Symbols:**

```
ffffffff81ba18c0-ffffffff81ba19ab: __auxiliary_driver_register (STB_GLOBAL)
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
