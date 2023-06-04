# ESP32_mini_8Port_WLED
<p align="center">
               
[<img src="https://img.shields.io/github/v/tag/w4b-zero/ESP32_mini_8Port_WLED?label=Relase&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAABhGlDQ1BJQ0MgcHJvZmlsZQAAKJF9kT1Iw1AUhU9TtVIqHewg4pChOlkQFXHUKhShQqgVWnUweekfNDEkKS6OgmvBwZ%2FFqoOLs64OroIg%2BAPi6uKk6CIl3pcUWsR44fE%2Bzrvn8N59gNCoMs3qGgM03TYzqaSYy6%2BIoVf0IIgoAgjLzDJmJSkN3%2Fq6pz6quwTP8u%2F7s%2FrUgsWAgEg8wwzTJl4nntq0Dc77xDFWllXic%2BJRky5I%2FMh1xeM3ziWXBZ4ZM7OZOeIYsVjqYKWDWdnUiCeJ46qmU76Q81jlvMVZq9ZY6578hZGCvrzEdVpDSGEBi5AgQkENFVRhI0G7ToqFDJ0nffyDrl8il0KuChg55rEBDbLrB%2F%2BD37O1ihPjXlIkCXS%2FOM7HMBDaBZp1x%2Fk%2BdpzmCRB8Bq70tn%2BjAUx%2Fkl5va%2FEjILoNXFy3NWUPuNwBBp4M2ZRdKUhLKBaB9zP6pjzQfwuEV725tc5x%2BgBkaVbpG%2BDgEBgpUfaaz7t7O%2Bf2b09rfj%2FJPHJjkWAKcAAAAAlwSFlzAAAN1wAADdcBQiibeAAAAAd0SU1FB%2BcGAw8EJudd3BAAAAEvSURBVEjHtZYxTsQwEEXfRIgNzbZcBIkjQE2FqFIimmVPAFeggRPQoaViQwsNBfSIkwAS2k%2FjIBMSx86akSJFk8k8%2Fz%2BOFfjnsOZG0hQ4Arb9fCsEvAE3ZvYVTZE0lfSq%2BLiTtBWtQNIxcAV8AM9upV2xCey69%2B6BAzN7j1Fw5lb2GFE7k7Ry9fWQkqLD47Bkswtg7mr3gdsQpGgPO8rX35C9EKQYsKOQVLmrGIAsJJVDM3ho5Stv51RjZjLKooGZLP7YJem8R0GvRUlKPIue1jkWOiCT5sGhS64kzTJC5k1yw33%2BuSC163XtJ0tJSw9ymk1BLkir%2BfJnBjkgHQMuQ8VJkNQDMAkyqnksJMmWVMhaK4%2BA1Nma90DkbcUy6q8iEjIBToAd4AW4NLPP0DvfUiJxtCJLzP0AAAAASUVORK5CYII%3D&style=plastic">](https://github.com/w4b-zero/ESP32_mini_8Port_WLED/releases)
 &nbsp; 
[<img src="https://img.shields.io/github/last-commit/w4b-zero/ESP32_mini_8Port_WLED?style=plastic&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAABhWlDQ1BJQ0MgcHJvZmlsZQAAKJF9kT1Iw0AcxV9TtSIVBTuIOASpgmBBVMRRq1CECqFWaNXB5NIvaNKQpLg4Cq4FBz8Wqw4uzro6uAqC4AeIq4uToouU+L+k0CLWg+N+vLv3uHsHCNUi06y2cUDTbTMRi4qp9KoYeEUH/OjFEEZlZhlzkhRHy/F1Dx9f7yI8q/W5P0e3mrEY4BOJZ5lh2sQbxNObtsF5nzjE8rJKfE48ZtIFiR+5rnj8xjnnssAzQ2YyMU8cIhZzTaw0McubGvEUcVjVdMoXUh6rnLc4a8Uyq9+TvzCY0VeWuU5zEDEsYgkSRCgoo4AibERo1UmxkKD9aAv/gOuXyKWQqwBGjgWUoEF2/eB/8LtbKzs54SUFo0D7i+N8DAOBXaBWcZzvY8epnQD+Z+BKb/hLVWDmk/RKQwsfAT3bwMV1Q1P2gMsdoP/JkE3Zlfw0hWwWeD+jb0oDfbdA15rXW30fpw9AkrqK3wAHh8BIjrLXW7y7s7m3f8/U+/sBa05ypE2o5wYAAAAJcEhZcwAADdcAAA3XAUIom3gAAAAHdElNRQfnBgMQJQCutahDAAABFklEQVRIx+2UO0pDQRSGv9GQ0qRKoZ2YCBZZQlYQXYBrcAHiCq5oG1egWNlIcBc210REEDfgA7VKiH5pBpQYL5cbbSQ/DMyc/5/zmMeBOf49Ql6hugQ04vI2hPD6KxmoDfVMHfqJYbTVZ3XeUl/UJzVR2+pmnD9HrlXUeU19VK/U5Sn8itpTH9RakQD78SjqGZr1qEmKBLhRz3Pouur1T/yCmvodI2AV6OfIpQesqaMpftISkADNiU1DYAeo5AhQAd6ADlCe4NKs0i/UO3UxQ1NS79VukTvYimXuZmj2oqZd9KmeqB/qgVr9Yq+qh5E7nuWjldUj9V0dqJdxDKKto5Zn7kVqE9gGNqKpD5yGENJ5O5/j7zEGJeQt/ASY9sUAAAAASUVORK5CYII=">](https://github.com/w4b-zero/ESP32_mini_8Port_WLED/commit/main) &nbsp; 
[<img src="https://img.shields.io/github/watchers/w4b-zero/ESP32_mini_8Port_WLED?style=plastic&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAABhWlDQ1BJQ0MgcHJvZmlsZQAAKJF9kT1Iw0AcxV9TtSIVBTuIOASpgmBBVMRRq1CECqFWaNXB5NIvaNKQpLg4Cq4FBz8Wqw4uzro6uAqC4AeIq4uToouU+L+k0CLWg+N+vLv3uHsHCNUi06y2cUDTbTMRi4qp9KoYeEUH/OjFEEZlZhlzkhRHy/F1Dx9f7yI8q/W5P0e3mrEY4BOJZ5lh2sQbxNObtsF5nzjE8rJKfE48ZtIFiR+5rnj8xjnnssAzQ2YyMU8cIhZzTaw0McubGvEUcVjVdMoXUh6rnLc4a8Uyq9+TvzCY0VeWuU5zEDEsYgkSRCgoo4AibERo1UmxkKD9aAv/gOuXyKWQqwBGjgWUoEF2/eB/8LtbKzs54SUFo0D7i+N8DAOBXaBWcZzvY8epnQD+Z+BKb/hLVWDmk/RKQwsfAT3bwMV1Q1P2gMsdoP/JkE3Zlfw0hWwWeD+jb0oDfbdA15rXW30fpw9AkrqK3wAHh8BIjrLXW7y7s7m3f8/U+/sBa05ypE2o5wYAAAAJcEhZcwAADdcAAA3XAUIom3gAAAAHdElNRQfnBgMQIw4fVyLCAAABc0lEQVRIx+3VsU7UQRAG8FlD6dGIjTZiUAk2WslrYIsIFkgH8hIiT6A+BQI2Gumw5gE0AQps1eqiZ/KjGSMc7P+OAzsm2WSz+823OzPfzkZcWg8rvQAoEfEwIu5ExI1c/hYRXyJip5RioJNxHavYV7f9xIychbhgGT/xG2uYxgRaOSbwBO/QwQ+8yGgbyVtJCBu428eF7mEzfdZwtQYcxue89eIAKV1M3220ujeHsIVfmKoQ3MbzHKMVzFQe8hFDRzdWM8SZiuMztI8Ut425CnY2Ma/+LkziD1433Lx9ioLaDZG8Sc7JyNTsncjbP/BCg0znG8Syh60r/dRvwL34nyl6m5yPuos8W3GYO6XITVhY6Zbpp5RYTaajmM9xq4J5nBwfjsn0gh7aUvWhVVrFJsb7IB7H+56toqvZLWUD62AdM7ifUQ7n/Gn2qw6+Z6soZwl5BCvYbXgHu3iJa+f9cB5ExFhE3Mzlg4j4WkrZufyzz22HLVGbc9t11cgAAAAASUVORK5CYII=">](https://github.com/w4b-zero/ESP32_mini_8Port_WLED/watchers) &nbsp; 
[<img src="https://img.shields.io/github/license/w4b-zero/ESP32_mini_8Port_WLED?style=plastic&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAABhWlDQ1BJQ0MgcHJvZmlsZQAAKJF9kT1Iw0AcxV9TtSIVBTuIOASpgmBBVMRRq1CECqFWaNXB5NIvaNKQpLg4Cq4FBz8Wqw4uzro6uAqC4AeIq4uToouU+L+k0CLWg+N+vLv3uHsHCNUi06y2cUDTbTMRi4qp9KoYeEUH/OjFEEZlZhlzkhRHy/F1Dx9f7yI8q/W5P0e3mrEY4BOJZ5lh2sQbxNObtsF5nzjE8rJKfE48ZtIFiR+5rnj8xjnnssAzQ2YyMU8cIhZzTaw0McubGvEUcVjVdMoXUh6rnLc4a8Uyq9+TvzCY0VeWuU5zEDEsYgkSRCgoo4AibERo1UmxkKD9aAv/gOuXyKWQqwBGjgWUoEF2/eB/8LtbKzs54SUFo0D7i+N8DAOBXaBWcZzvY8epnQD+Z+BKb/hLVWDmk/RKQwsfAT3bwMV1Q1P2gMsdoP/JkE3Zlfw0hWwWeD+jb0oDfbdA15rXW30fpw9AkrqK3wAHh8BIjrLXW7y7s7m3f8/U+/sBa05ypE2o5wYAAAAJcEhZcwAADdcAAA3XAUIom3gAAAAHdElNRQfnBgMQJg8VJ+YRAAAB2ElEQVRIx+WWsWsUURDGf++y4EG4CEmtoCAkjRaiCArxVKKdgoqlQlJopZ1E9DD+D1raaBGwUwsbiWitISoIEkIQRNNpEEzA82czJ8tm3bsL2OhUOzPfzPe9eW/3LfxXpt5Rb/dTk/XJMdavqKwH1SeAPeFuj9jV8BdSSk82O44RddbuNquOdGs2rq6XFK+p02oWuDl1Lp6zyK2V1K2r43mCYbWl3g3Ae/W6OloQ8psgFxtTb0SN0aOlDpet5FaAVtWtJfkNBBEfUr9G7Uw+V8uB6sBF4C3QACb72LIpYChqL0WvDSqmQsFh9Zm63Jl9lxENqEuRa0aPyTKCBfW1mtRTATzdA8GZwJ4Mf159o6Y86FiAzodfUxfV5z0QvIgVDIR/IXodzYMeqyv52alXArj/TwTq3sBczsW2qJ/UR53ALrWttgrKGuoX9V4Fwf2yE6feVH+qoxkwEafpoHoOWAYGgUNAGzhecXomgB/AtPoS+AbsAJpAAo6g1tUZ9XPhbWyrT9UDFSvYpz5UvxdqF9Vraj3ljxuwG9gGrALvUkorxU0GSCk1C/HBUN4APqaUPmz2A1j6JldZ7W9fUlmF2rPAzkK4eB90bCml9KDfcczbu736d38UfgH+YI1qJvNNrAAAAABJRU5ErkJggg==">](https://raw.githubusercontent.com/w4b-zero/ESP32_mini_8Port_WLED/main/LICENSE) &nbsp; 
[![IMAGE_ALT](https://img.shields.io/github/languages/code-size/w4b-zero/ESP32_mini_8Port_WLED?style=plastic&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAABhWlDQ1BJQ0MgcHJvZmlsZQAAKJF9kT1Iw0AcxV9TtSIVBTuIOASpgmBBVMRRq1CECqFWaNXB5NIvaNKQpLg4Cq4FBz8Wqw4uzro6uAqC4AeIq4uToouU%2BL%2Bk0CLWg%2BN%2BvLv3uHsHCNUi06y2cUDTbTMRi4qp9KoYeEUH%2FOjFEEZlZhlzkhRHy%2FF1Dx9f7yI8q%2FW5P0e3mrEY4BOJZ5lh2sQbxNObtsF5nzjE8rJKfE48ZtIFiR%2B5rnj8xjnnssAzQ2YyMU8cIhZzTaw0McubGvEUcVjVdMoXUh6rnLc4a8Uyq9%2BTvzCY0VeWuU5zEDEsYgkSRCgoo4AibERo1UmxkKD9aAv%2FgOuXyKWQqwBGjgWUoEF2%2FeB%2F8LtbKzs54SUFo0D7i%2BN8DAOBXaBWcZzvY8epnQD%2BZ%2BBKb%2FhLVWDmk%2FRKQwsfAT3bwMV1Q1P2gMsdoP%2FJkE3Zlfw0hWwWeD%2Bjb0oDfbdA15rXW30fpw9AkrqK3wAHh8BIjrLXW7y7s7m3f8%2FU%2B%2FsBa05ypE2o5wYAAAAJcEhZcwAADdcAAA3XAUIom3gAAAAHdElNRQfnBgMRBAFU7%2BcBAAABg0lEQVRIx72WsUtbURTGf%2FdhKOpmN5eSwdVOMYUWCkKhVOPgIM1f4JjRNWMnO5R2Lx1FJylth1QdBEFQ3MShVB0FkUihWvx1uYXweGmSl5g7nvu9%2B53vnPMdHgzzqHPqud2fn2rlf2%2BGFMEZcAl87pDLM%2BApsA88BqohhPVuFKjWu8DVI3ZMbah%2F1GoWNumnpCGEX8A8sAN8yiJJ%2Bu1bJFkAdoGP6Z7kJfgdS%2FUwklwDr4BD4N0gCL4At8DFv3ECmkAJeNQKHMlZlgN1BqgA4xnT1XY6jtTXffioHtVkKwghTA%2FavMl9b4ekRd6EuqWupmS%2FVb%2BrE7kJ1MloljLwLYX5CjwBtiOu58YU1RO1qb5og3muXqk%2F1Klemox6rN6opQ6JlCLuuBeCBFgDCkBNLbT5sADUIm4tT5lW1Dt1Ux1N3T1QN6Jh3%2FTqg9bL5bh236fiH2J8OY%2FR0oBZtZyKldXZQTm5kbF39vox2khGFktAMed7i8BZJ5lH5j%2Bn6suh%2Fqn8BbHck7yUqD2nAAAAAElFTkSuQmCC)](https://github.com/w4b-zero/ESP32_mini_8Port_WLED/archive/refs/heads/main.zip) <br> 
[![Discord](https://img.shields.io/discord/1106048601269993482?logo=discord&logoColor=ffffff&style=plastic&color=5865F2)](https://discord.gg/kteShSHU) &nbsp; 
[![KiCad](https://img.shields.io/static/v1?label=Editor&message=KiCad&style=plastic&logo=kicad&color=314CB0)](https://www.kicad.org/) &nbsp; 
[![JLCPCB](https://img.shields.io/static/v1?label=PCB&message=JLCPCB&style=plastic&color=5865F2&logoColor=ffffff&logo=data:image/png;base64,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)](https://jlcpcb.com/)
</p>

PCB and KiCad-Files for a 8Port WLED ESP32_mini Board<br>
<img src="/images/ESP32_mini_8Port_WLED_top.png" width="400px"></a> <br>
<ul>
<li>Gerber Files</li>
<li>KiCad 7 Project Files</li>
<li>included used Library Files where not in official KiCad-Library for KiCad 7</li>
  </ul>
<br>

## KiCad Symbol Librarys

<ul>
<li>button:SW_PUSH-12mm</li>
<li>button:SW_PUSH-12mm_roundKnob</li>
<li>button:SW_PUSH-12mm_squareKnob</li>
<li>eec:TSOP38238</li>
<li>ESP32_mini:mini_esp32</li>
<li>wemos_mini:WeMos_D1_mini</li>
  </ul>
<br> 

## KiCad Footprints inkl. 3D-Models

<ul>
<li>button:SW_PUSH-12mm</li>
<li>button:SW_PUSH-12mm_roundKnob</li>
<li>button:SW_PUSH-12mm_squareKnob</li>
<li>eec:Vishay_Semiconductors-TSOP38238-Manufacturer_Recommended</li>
<li>ESP32_mini:ESP32_mini-only-connector</li>
<li>ESP32_mini:ESP32_mini-with-pin-header</li>
<li>ESP32_mini:ESP32_mini-with-pin-header-and-connector</li>
<li>logocircuit:brain</li>
<li>logocircuit:brainbig</li>
<li>logocircuit:WLED_Logo_micro</li>
<li>logocircuit:WLED_Logo_micro_cu</li>
<li>logocircuit:WLED_Logo_mini</li>
<li>logocircuit:zeroTM_Logo</li>
<li>logocircuit:zeroTM_Logo_layerB</li>
<li>logocircuit:zeroTM_Logo_micro</li>
<li>logocircuit:zeroTM_Logo_micro_cu</li>
<li>logocircuit:zeroTM_Logo_mini</li>
<li>mounts:MountingHole_3.2mm_M3_Pad_Via</li>
<li>Terminal_dg306:TerminalBlock_RND_205-00045_1x02_P5.00mm_Horizontal</li>
<li>Terminal_dg306:TerminalBlock_RND_205-00046_1x03_P5.00mm_Horizontal</li>
<li>Terminal_dg306:TerminalBlock_RND_205-00047_1x04_P5.00mm_Horizontal</li>
<li>Terminal_dg306:TerminalBlock_RND_205-00048_1x05_P5.00mm_Horizontal</li>
<li>Terminal_dg306:TerminalBlock_RND_205-00049_1x06_P5.00mm_Horizontal</li>
<li>Terminal_dg306:TerminalBlock_RND_205-00050_1x07_P5.00mm_Horizontal</li>
<li>Terminal_dg306:TerminalBlock_RND_205-00051_1x08_P5.00mm_Horizontal</li>
<li>Terminal_dg306:TerminalBlock_RND_205-00052_1x09_P5.00mm_Horizontal</li>
<li>Terminal_dg306:TerminalBlock_RND_205-00053_1x10_P5.00mm_Horizontal</li>
<li>Terminal_dg306:TerminalBlock_RND_205-00054_1x11_P5.00mm_Horizontal</li>
<li>Terminal_dg306:TerminalBlock_RND_205-00055_1x12_P5.00mm_Horizontal</li>
<li>wemos-d1-mini:wemos-d1-mini-connectors-only</li>
<li>wemos-d1-mini:wemos-d1-mini-embedded</li>
<li>wemos-d1-mini:wemos-d1-mini-with-pin-header</li>
  <li>wemos-d1-mini:wemos-d1-mini-with-pin-header-and-connector</li>
  </ul>
<br>

## WLED-Board for ESP23 mini in use

#### Test
<img src="/images/IMG_20230531_165236.jpg" width="400px"><br>

#### Connected
<img src="/images/IMG_20230601_200542.jpg" width="400px"><br>

#### Matrix with 2048 WS2812 LEDs
<img src="/images/IMG_20230601_200719.jpg" width="400px"><br>

#### ESP32_mini_8Port_WLED drived the Matrix
<img src="/images/IMG_20230601_201008.jpg" width="400px"><br>
Firmware: WLED https://github.com/Aircoookie/WLED <br>
Leds: 2048 (256 to each port)


## Youtube Videos

#### 2048 WS2812b Led's. first test.<br>
[![IMAGE_ALT](https://img.youtube.com/vi/6V0AxyubT9o/0.jpg)](https://www.youtube.com/watch?v=6V0AxyubT9o)

#### 2048 WS2812b Led's - capture the screen test.<br>
[![IMAGE_ALT](https://img.youtube.com/vi/_0qXEe0vF80/0.jpg)](https://www.youtube.com/watch?v=_0qXEe0vF80)

#### 2048 WS2812b Led's - colorscroll<br>
[![IMAGE_ALT](https://img.youtube.com/vi/-9pOgiMY1iY/0.jpg)](https://www.youtube.com/watch?v=-9pOgiMY1iY)

Firmware: WLED https://github.com/Aircoookie/WLED <br>
PC Software: Jinx! http://www.live-leds.de/ <br>
Leds: 2048 (512 to each port) <br>
<br>

## My Discord Server

<a href="https://discord.gg/mWFdm5Hg"><img src="https://discord.com/api/guilds/1106048601269993482/widget.png?style=banner2" width="25%"></a> <br>

<br>

## <img src="https://raw.githubusercontent.com/Aircoookie/Akemi/master/akemi/999_wled.png" width="100"> usefull Links!! <img src="https://raw.githubusercontent.com/Aircoookie/Akemi/master/akemi/997_cheerful_with_hearts_cycle.gif" width="25">

WLED Projectpage:  https://kno.wled.ge/ <br>

Join the WLED Discord server to discuss everything about WLED!<br>
<a href="https://discord.gg/KuqP7NE"><img src="https://discordapp.com/api/guilds/473448917040758787/widget.png?style=banner2" width="25%"></a> <br>

Check out the WLED [Discourse forum](https://wled.discourse.group)! <br> 

Firmware: WLED Sourcecode https://github.com/Aircoookie/WLED <br>

