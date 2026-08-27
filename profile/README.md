<p align="center"> <a href="https://easynavigation.github.io/" target="blank"><img src="https://github.com/EasyNavigation/.github/blob/main/easynav_logo.png" width="250" alt="" /></a> </p>
<h1 align="center"></h1>
<p align="center"> 

<h2 align="center">
  🌐 <a href="https://easynavigation.github.io/" target="_blank">https://easynavigation.github.io/</a>
</h2>

## 🧭 EasyNavigation (EasyNav)

**EasyNavigation (EasyNav)** is an open-source navigation system for **ROS 2**, designed to be:

✅ **Representation-agnostic**, supporting a wide variety of environment models: 2D costmaps, elevation-aware gridmaps, Octomap-based 3D representations, raw point clouds, or hybrid combinations.  
⚡ **Real-time capable**, minimizing latency between perception and action.  
🧩 **Modular**, through a plugin architecture and reusable navigation stacks.  
🚀 **Lightweight and simple to deploy**, using a single binary and a parameter file for configuration.  
🧪 **Simulation-ready**, thanks to a rich collection of PlayGrounds with different robots and environments.

EasyNav is developed by the **[Intelligent Robotics Lab](https://intelligentroboticslab.gsyc.urjc.es/)** at **Universidad Rey Juan Carlos**, and aims to be a flexible, extensible, and practical alternative to existing ROS 2 navigation stacks such as **Nav2**.

---

<img width="240" height="47" alt="MICIU+Cofinanciado+AEI" src="https://github.com/user-attachments/assets/fedfcf13-6af6-43d7-8290-fe22da4e1db0" />
<img width="240" height="50" alt="eu_funded_en" src="https://github.com/user-attachments/assets/b11da974-9201-4f79-902e-c9c20e8aa7a4" />
Funded by the European Union through the Horizon Europe programme under Grant Agreement No. 101070254 (CoreSense), and by MICIU/AEI/10.13039/501100011033 and ERDF/EU under grants PERMAP PID2024-161761OB-C21 and PLANNAV PID2024-161761OB-C22 (AURORAS).

---

## 🧩 CI Status
| Repository | Doxygen | Rolling | Lyrical | Kilted | Jazzy | Humble |
|-------------|----------|----------|----------|----------|----------|----------|
| [**EasyNavigation**](https://github.com/EasyNavigation/EasyNavigation) | [![Doxygen Deployment](https://github.com/EasyNavigation/EasyNavigation/actions/workflows/doxygen-doc.yml/badge.svg)](https://github.com/EasyNavigation/EasyNavigation/actions/workflows/doxygen-doc.yml) | [![rolling](https://github.com/EasyNavigation/EasyNavigation/actions/workflows/rolling.yaml/badge.svg?branch=rolling)](https://github.com/EasyNavigation/EasyNavigation/actions/workflows/rolling.yaml) | [![lyrical](https://github.com/EasyNavigation/EasyNavigation/actions/workflows/lyrical.yaml/badge.svg?branch=lyrical)](https://github.com/EasyNavigation/EasyNavigation/actions/workflows/lyrical.yaml) | [![kilted](https://github.com/EasyNavigation/EasyNavigation/actions/workflows/kilted.yaml/badge.svg?branch=kilted)](https://github.com/EasyNavigation/EasyNavigation/actions/workflows/kilted.yaml) | [![jazzy](https://github.com/EasyNavigation/EasyNavigation/actions/workflows/jazzy.yaml/badge.svg?branch=jazzy)](https://github.com/EasyNavigation/EasyNavigation/actions/workflows/jazzy.yaml) | [![humble](https://github.com/EasyNavigation/EasyNavigation/actions/workflows/humble.yaml/badge.svg?branch=humble)](https://github.com/EasyNavigation/EasyNavigation/actions/workflows/humble.yaml) |
| [**NavMap**](https://github.com/EasyNavigation/NavMap) | [![Doxygen Deployment](https://github.com/EasyNavigation/NavMap/actions/workflows/doxygen-doc.yml/badge.svg)](https://github.com/EasyNavigation/NavMap/actions/workflows/doxygen-doc.yml) | [![rolling](https://github.com/EasyNavigation/NavMap/actions/workflows/rolling.yaml/badge.svg?branch=rolling)](https://github.com/EasyNavigation/NavMap/actions/workflows/rolling.yaml) | [![lyrical](https://github.com/EasyNavigation/NavMap/actions/workflows/lyrical.yaml/badge.svg?branch=lyrical)](https://github.com/EasyNavigation/NavMap/actions/workflows/lyrical.yaml) | [![kilted](https://github.com/EasyNavigation/NavMap/actions/workflows/kilted.yaml/badge.svg?branch=kilted)](https://github.com/EasyNavigation/NavMap/actions/workflows/kilted.yaml) | [![jazzy](https://github.com/EasyNavigation/NavMap/actions/workflows/jazzy.yaml/badge.svg?branch=jazzy)](https://github.com/EasyNavigation/NavMap/actions/workflows/jazzy.yaml) | [![humble](https://github.com/EasyNavigation/NavMap/actions/workflows/humble.yaml/badge.svg?branch=humble)](https://github.com/EasyNavigation/NavMap/actions/workflows/humble.yaml) |
| [**easynav_plugins**](https://github.com/EasyNavigation/easynav_plugins) | [![Doxygen Deployment](https://github.com/EasyNavigation/easynav_plugins/actions/workflows/doxygen-doc.yml/badge.svg)](https://github.com/EasyNavigation/easynav_plugins/actions/workflows/doxygen-doc.yml) | [![rolling](https://github.com/EasyNavigation/easynav_plugins/actions/workflows/rolling.yaml/badge.svg?branch=rolling)](https://github.com/EasyNavigation/easynav_plugins/actions/workflows/rolling.yaml) | [![lyrical](https://github.com/EasyNavigation/easynav_plugins/actions/workflows/lyrical.yaml/badge.svg?branch=lyrical)](https://github.com/EasyNavigation/easynav_plugins/actions/workflows/lyrical.yaml) | [![kilted](https://github.com/EasyNavigation/easynav_plugins/actions/workflows/kilted.yaml/badge.svg?branch=kilted)](https://github.com/EasyNavigation/easynav_plugins/actions/workflows/kilted.yaml) | [![jazzy](https://github.com/EasyNavigation/easynav_plugins/actions/workflows/jazzy.yaml/badge.svg?branch=jazzy)](https://github.com/EasyNavigation/easynav_plugins/actions/workflows/jazzy.yaml) | [![humble](https://github.com/EasyNavigation/easynav_plugins/actions/workflows/humble.yaml/badge.svg?branch=humble)](https://github.com/EasyNavigation/easynav_plugins/actions/workflows/humble.yaml) |
| [**yaets**](https://github.com/fmrico/yaets) | [![Doxygen Deployment](https://github.com/fmrico/yaets/actions/workflows/doxygen-doc.yml/badge.svg)](https://github.com/fmrico/yaets/actions/workflows/doxygen-doc.yml) | [![rolling](https://github.com/fmrico/yaets/actions/workflows/rolling.yaml/badge.svg?branch=rolling)](https://github.com/fmrico/yaets/actions/workflows/rolling.yaml) | [![lyrical](https://github.com/fmrico/yaets/actions/workflows/lyrical.yaml/badge.svg?branch=lyrical)](https://github.com/fmrico/yaets/actions/workflows/lyrical.yaml) | [![kilted](https://github.com/fmrico/yaets/actions/workflows/kilted.yaml/badge.svg?branch=kilted)](https://github.com/fmrico/yaets/actions/workflows/kilted.yaml) | [![jazzy](https://github.com/fmrico/yaets/actions/workflows/jazzy.yaml/badge.svg?branch=jazzy)](https://github.com/fmrico/yaets/actions/workflows/jazzy.yaml) |  [![humble](https://github.com/fmrico/yaets/actions/workflows/humble.yaml/badge.svg?branch=humble)](https://github.com/fmrico/yaets/actions/workflows/humble.yaml) |

---

## 📦 Main Repositories

| Repository | Description |
|-------------|-------------|
| [**EasyNavigation**](https://github.com/EasyNavigation/EasyNavigation) | Core of the EasyNav system, providing the navigation core, plugin management, and runtime execution. |
| [**easynav_plugins**](https://github.com/EasyNavigation/easynav_plugins) | Collection of plugins implementing various **map managers**, **planners**, **localizers**, and **controllers**. |
| [**NavMap**](https://github.com/EasyNavigation/NavMap) | Surface-based map representation for navigable 3D environments, providing geometric and semantic layers for efficient navigation. |
| [**easynav_gridmap_stack**](https://github.com/EasyNavigation/easynav_gridmap_stack) | EasyNav stack built around **GridMaps** ([ANYbotics/grid_map](https://github.com/ANYbotics/grid_map)), integrating gridmap-based planners and controllers. |
| [**easynav_playground_kobuki**](https://github.com/EasyNavigation/easynav_playground_kobuki) | PlayGround with the **Kobuki** mobile robot in indoor simulation environments. |
| [**easynav_playground_summit**](https://github.com/EasyNavigation/easynav_playground_summit) | PlayGround featuring the **Summit XL** robot in outdoor environments. |

---

## 👥 Project Maintainers

| Name | Organization | GitHub | Role |
|------|---------------|--------|------|
| Francisco Martín Rico | Universidad Rey Juan Carlos | [fmrico](https://github.com/fmrico) | Project Lead |
| Francisco Miguel Moreno Olivo | Universidad Rey Juan Carlos | [butakus](https://github.com/butakus) | Core Developer |
| José Miguel Guerrero Hernández | Universidad Rey Juan Carlos | [jmguerreroh](https://github.com/jmguerreroh) | Developer |
| Juan Sebastián Cely Gutiérrez | Universidad Rey Juan Carlos | [juanscelyg](https://github.com/juanscelyg) | Developer |
| Esther Aguado González | Universidad Rey Juan Carlos | [estherag](https://github.com/estherag) | Developer |
| Francisco José Romero Ramírez | Universidad Rey Juan Carlos | [kiko2r](https://github.com/kiko2r) | Developer |
| Miguel de Miguel Paraiso | Universidad Rey Juan Carlos | [midemig](https://github.com/midemig) | Advisor |
| Jorge Beltrán de la Cita | Universidad Rey Juan Carlos | [beltransen](https://github.com/beltransen) | Advisor |

---

📋 Roadmap Project: [RoadMap](https://github.com/EasyNavigation/EasyNavigation/blob/rolling/ROADMAP.md)

---

<p align="center">
  <a href="https://intelligentroboticslab.gsyc.urjc.es/">
    <strong>Intelligent Robotics Lab – Universidad Rey Juan Carlos</strong>
  </a>
</p>
