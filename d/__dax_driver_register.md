# Function: <code>__dax_driver_register</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:459
Inline: False
```
**Symbols:**

```
ffffffff81740553-ffffffff81740580: __dax_driver_register.cold (STB_LOCAL)
ffffffff81740050-ffffffff817400c7: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81764230)
Location: drivers/dax/bus.c:459
Inline: False
```
**Symbols:**

```
ffffffff81764230-ffffffff817642c3: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81823d20)
Location: drivers/dax/bus.c:473
Inline: False
```
**Symbols:**

```
ffffffff81823d20-ffffffff81823db7: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81833200)
Location: drivers/dax/bus.c:1389
Inline: False
```
**Symbols:**

```
ffffffff81833200-ffffffff81833297: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818163f0)
Location: drivers/dax/bus.c:1390
Inline: False
```
**Symbols:**

```
ffffffff818163f0-ffffffff818164d4: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818a0910)
Location: drivers/dax/bus.c:1388
Inline: False
```
**Symbols:**

```
ffffffff818a0910-ffffffff818a09f4: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff819e9f50)
Location: drivers/dax/bus.c:1418
Inline: False
```
**Symbols:**

```
ffffffff819e9f50-ffffffff819ea052: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81b66980)
Location: drivers/dax/bus.c:1418
Inline: False
```
**Symbols:**

```
ffffffff81b66980-ffffffff81b66a82: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81bb9e00)
Location: drivers/dax/bus.c:1442
Inline: False
```
**Symbols:**

```
ffffffff81bb9e00-ffffffff81bb9e5c: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81c0e460)
Location: drivers/dax/bus.c:1445
Inline: False
```
**Symbols:**

```
ffffffff81c0e460-ffffffff81c0e4bc: __dax_driver_register (STB_GLOBAL)
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
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffff800010964788)
Location: drivers/dax/bus.c:459
Inline: False
```
**Symbols:**

```
ffff800010964788-ffff80001096483c: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (c0a3b0cc)
Location: drivers/dax/bus.c:459
Inline: False
```
**Symbols:**

```
c0a3b0cc-c0a3b174: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (c000000000a1aad0)
Location: drivers/dax/bus.c:459
Inline: False
```
**Symbols:**

```
c000000000a1aad0-c000000000a1aba8: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffe0005d1442)
Location: drivers/dax/bus.c:459
Inline: False
```
**Symbols:**

```
ffffffe0005d1442-ffffffe0005d14f6: __dax_driver_register (STB_GLOBAL)
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
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81718920)
Location: drivers/dax/bus.c:459
Inline: False
```
**Symbols:**

```
ffffffff81718920-ffffffff817189b3: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff816f0e50)
Location: drivers/dax/bus.c:459
Inline: False
Direct callers:
  - drivers/dax/device.c:dax_init
```
**Symbols:**

```
ffffffff816f0e50-ffffffff816f0ee3: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff817576f0)
Location: drivers/dax/bus.c:459
Inline: False
```
**Symbols:**

```
ffffffff817576f0-ffffffff81757783: __dax_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver *dax_drv, struct module *module, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81772b90)
Location: drivers/dax/bus.c:459
Inline: False
```
**Symbols:**

```
ffffffff81772b90-ffffffff81772c23: __dax_driver_register (STB_GLOBAL)
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
