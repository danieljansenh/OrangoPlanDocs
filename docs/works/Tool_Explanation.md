---
hide:
  # - navigation
  - toc
---


## Analysis
These Grasshopper analysis tools allow designers to test and compare spatial, environmental, and performance criteria directly within parametric models. By integrating data-driven insights—such as accessibility, reachability or circulation patterns—into the design workflow. This enables architects, planners, and urban designers to move beyond intuition alone, creating spatial and urban strategies that are more efficient, resilient, and responsive to human and environmental needs.

  <table style="width:100%; border-collapse: collapse; font-family: Arial, sans-serif;">
    <thead>
      <tr style="background-color: #f5f5f5;">
        <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd;">Tool</th>
        <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd;">Function</th>
        <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd;">Input</th>
        <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd;">Output</th>
      </tr>
      <tr style="background-color: #f5f5f5;">
        <th style="text-align:center; padding:8px; border:1px solid #ddd;">Initial</th>
        <th style="text-align:center; padding:8px; border:1px solid #ddd;">Name</th>
        <th style="text-align:center; padding:8px; border:1px solid #ddd;">Description</th>
        <th style="text-align:center; padding:8px; border:1px solid #ddd;">Initial</th>
        <th style="text-align:center; padding:8px; border:1px solid #ddd;">Name</th>
        <th style="text-align:center; padding:8px; border:1px solid #ddd;">Description</th>
      </tr>
    </thead>
    <tbody>
      <!-- Centroid Tool -->
      <tr>
        <td style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
          <div style="display:flex; flex-direction:column; align-items:center;">
            <img src="../../assets/A_Centroid.png" alt="Centroid" style="height:25px; margin-bottom:5px;">
            <span>Centroid</span>
          </div>
        </td>
        <td style="padding:12px; border:1px solid #ddd;">Analyze centroid of each closed curve</td>
        <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
        <td style="padding:12px; border:1px solid #ddd;">Curves</td>
        <td style="padding:12px; border:1px solid #ddd;">Closed curves to analyze</td>
        <td style="text-align:center; padding:12px; border:1px solid #ddd;">Ct</td>
        <td style="padding:12px; border:1px solid #ddd;">Centroids</td>
        <td style="padding:12px; border:1px solid #ddd;">Center points and area of closed curves</td>
      </tr>
      <!-- Convex Hull Tool -->
      <tr style="background-color: #f9f9f9;">
          <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
              <div style="display:flex; flex-direction:column; align-items:center;">
                  <img src="../../assets/A_Convex_Hull.png" alt="Convex Hull" style="height:25px; margin-bottom:5px;">
                  <span>Convex Hull</span>
              </div>
          </td>
          <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Create convex hull form points</td>
          <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
          <td style="padding:12px; border:1px solid #ddd;">Curves</td>
          <td style="padding:12px; border:1px solid #ddd;">Curves to compute convex hull</td>
          <td style="text-align:center; padding:12px; border:1px solid #ddd;">Pts</td>
          <td style="padding:12px; border:1px solid #ddd;">Convex Hull Points</td>
          <td style="padding:12px; border:1px solid #ddd;">Points of the convex hull</td>
      </tr>
      <tr style="background-color: #f9f9f9;">
          <td style="border:1px solid #ddd;"></td>
          <td style="border:1px solid #ddd;"></td>
          <td style="border:1px solid #ddd;"></td>
          <td style="text-align:center; padding:12px; border:1px solid #ddd;">Hull</td>
          <td style="padding:12px; border:1px solid #ddd;">Convex Hull</td>
          <td style="padding:12px; border:1px solid #ddd;">Convex hull as a closed polyline</td>
      </tr>
      <tr style="background-color: #f9f9f9;">
          <td style="border:1px solid #ddd;"></td>
          <td style="border:1px solid #ddd;"></td>
          <td style="border:1px solid #ddd;"></td>
          <td style="text-align:center; padding:12px; border:1px solid #ddd;">A</td>
          <td style="padding:12px; border:1px solid #ddd;">Area</td>
          <td style="padding:12px; border:1px solid #ddd;">Area of the convex hull</td>
      </tr>
      <!-- Service Catchment Tool -->
      <tr>
          <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
              <div style="display:flex; flex-direction:column; align-items:center;">
                  <img src="../../assets/A_Service_Catchment.png" alt="Service Catchment" style="height:25px; margin-bottom:5px;">
                  <span>Service Catchment</span>
              </div>
          </td>
          <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Analyzes road service coverage based on search radius</td>
          <td style="text-align:center; padding:12px; border:1px solid #ddd;">P</td>
          <td style="padding:12px; border:1px solid #ddd;">Points</td>
          <td style="padding:12px; border:1px solid #ddd;">Origin points to analyze</td>
          <td style="text-align:center; padding:12px; border:1px solid #ddd;">L</td>
          <td style="padding:12px; border:1px solid #ddd;">Network Lengths</td>
          <td style="padding:12px; border:1px solid #ddd;">Total length of catchment within the search radius</td>
      </tr>
      <tr>
          <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
          <td style="padding:12px; border:1px solid #ddd;">Network Curves</td>
          <td style="padding:12px; border:1px solid #ddd;">Network curves to analyze</td>
          <td style="text-align:center; padding:12px; border:1px solid #ddd;">B</td>
          <td style="padding:12px; border:1px solid #ddd;">Network Boundaries</td>
          <td style="padding:12px; border:1px solid #ddd;">Boundaries within the catchment radius</td>
      </tr>
      <tr>
          <td style="text-align:center; padding:12px; border:1px solid #ddd;">R</td>
          <td style="padding:12px; border:1px solid #ddd;">Search Radius</td>
          <td style="padding:12px; border:1px solid #ddd;">Catchment radius from origin points</td>
          <td colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color:#f9f9f9;">-</td>
      </tr>
      <!-- Shortest Path Tool -->
      <tr style="background-color: #f9f9f9;">
          <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
              <div style="display:flex; flex-direction:column; align-items:center;">
                  <img src="../../assets/A_Shortest_Path.png" alt="Shortest Path" style="height:25px; margin-bottom:5px;">
                  <span>Shortest Path</span>
              </div>
          </td>
          <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Computes the shortest path between two points along a network of curves</td>
          <td style="text-align:center; padding:12px; border:1px solid #ddd;">S</td>
          <td style="padding:12px; border:1px solid #ddd;">Start Point</td>
          <td style="padding:12px; border:1px solid #ddd;">Start point of the path</td>
          <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
          <td style="padding:12px; border:1px solid #ddd;">Shortest Path Curves</td>
          <td style="padding:12px; border:1px solid #ddd;">Shortest path as curves</td>
      </tr>
      <tr style="background-color: #f9f9f9;">
          <td style="text-align:center; padding:12px; border:1px solid #ddd;">E</td>
          <td style="padding:12px; border:1px solid #ddd;">End Point</td>
          <td style="padding:12px; border:1px solid #ddd;">End point of the path</td>
          <td style="text-align:center; padding:12px; border:1px solid #ddd;">L</td>
          <td style="padding:12px; border:1px solid #ddd;">Path Lengths</td>
          <td style="padding:12px; border:1px solid #ddd;">Shortest path lengths</td>
      </tr>
      <tr style="background-color: #f9f9f9;">
          <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
          <td style="padding:12px; border:1px solid #ddd;">Network Curves</td>
          <td style="padding:12px; border:1px solid #ddd;">Network curves to analyze</td>
          <td colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color:#f5f5f5;">-</td>
      </tr>
  </tbody>
</table>

The show's format consists of a combination of commercial television production elements and techniques which have evolved to reflect changes in American culture and audiences' viewing habits. It was the first children's TV show to use educational goals and a curriculum to shape its content, and the first show whose educational effects were formally studied. Its format and content have undergone significant changes over the years to reflect changes to its curriculum.

## Design
The show's format consists of a combination of commercial television production elements and techniques which have evolved to reflect changes in American culture and audiences' viewing habits. It was the first children's TV show to use educational goals and a curriculum to shape its content, and the first show whose educational effects were formally studied. Its format and content have undergone significant changes over the years to reflect changes to its curriculum.

<table style="width:100%; table-layout:auto; border-collapse: collapse;">

  <thead>
    <tr>
      <th style="text-align:center;">Tool</th>
      <th style="text-align:center;">Function</th>
      <th style="text-align:center;">Initial</th>
      <th style="text-align:center;">Name</th>
      <th style="text-align:center;">Description</th>
      <th style="text-align:center;">Initial</th>
      <th style="text-align:center;">Name</th>
      <th style="text-align:center;">Description</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td style="text-align:center;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/A_Centroid.png" alt="Centroid" style="height:25px; margin-bottom:5px;">
          <span>Centroid</span>
        </div>
      </td>
      <td>Analyze centroid of each closed curve</td>
      <td style="text-align:center;">C</td>
      <td>Curve</td>
      <td>Curves to compute convex hull</td>
      <td style="text-align:center;">C</td>
      <td>Curves</td>
      <td>Curves to compute convex hull</td>
    </tr>
  </tbody>

  <tbody>
    <tr>
      <td style="text-align:center;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/A_Centroid.png" alt="Centroid" style="height:25px; margin-bottom:5px;">
          <span>Centroid</span>
        </div>
      </td>
      <td>Analyze centroid of each closed curve</td>
      <td style="text-align:center;">C</td>
      <td>Curve</td>
      <td>Curves to compute convex hull</td>
      <td style="text-align:center;">C</td>
      <td>Curves</td>
      <td>Curves to compute convex hull</td>
    </tr>
  </tbody>

    <tbody>
    <tr>
      <td style="text-align:center;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/A_Centroid.png" alt="Centroid" style="height:25px; margin-bottom:5px;">
          <span>Centroid</span>
        </div>
      </td>
      <td>Analyze centroid of each closed curve</td>
      <td style="text-align:center;">C</td>
      <td>Curve</td>
      <td>Curves to compute convex hull</td>
      <td style="text-align:center;">C</td>
      <td>Curves</td>
      <td>Curves to compute convex hull</td>
    </tr>
  </tbody>

</table>


The show's format consists of a combination of commercial television production elements and techniques which have evolved to reflect changes in American culture and audiences' viewing habits. It was the first children's TV show to use educational goals and a curriculum to shape its content, and the first show whose educational effects were formally studied. Its format and content have undergone significant changes over the years to reflect changes to its curriculum.

## Design
The show's format consists of a combination of commercial television production elements and techniques which have evolved to reflect changes in American culture and audiences' viewing habits. It was the first children's TV show to use educational goals and a curriculum to shape its content, and the first show whose educational effects were formally studied. Its format and content have undergone significant changes over the years to reflect changes to its curriculum.

<table style="width:100%; table-layout:auto; border-collapse: collapse;">

  <thead>
    <tr>
      <th style="text-align:center;">Tool</th>
      <th style="text-align:center;">Function</th>
      <th style="text-align:center;">Initial</th>
      <th style="text-align:center;">Name</th>
      <th style="text-align:center;">Description</th>
      <th style="text-align:center;">Initial</th>
      <th style="text-align:center;">Name</th>
      <th style="text-align:center;">Description</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td style="text-align:center;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/A_Centroid.png" alt="Centroid" style="height:25px; margin-bottom:5px;">
          <span>Centroid</span>
        </div>
      </td>
      <td>Analyze centroid of each closed curve</td>
      <td style="text-align:center;">C</td>
      <td>Curve</td>
      <td>Curves to compute convex hull</td>
      <td style="text-align:center;">C</td>
      <td>Curves</td>
      <td>Curves to compute convex hull</td>
    </tr>
  </tbody>

  <tbody>
    <tr>
      <td style="text-align:center;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/A_Centroid.png" alt="Centroid" style="height:25px; margin-bottom:5px;">
          <span>Centroid</span>
        </div>
      </td>
      <td>Analyze centroid of each closed curve</td>
      <td style="text-align:center;">C</td>
      <td>Curve</td>
      <td>Curves to compute convex hull</td>
      <td style="text-align:center;">C</td>
      <td>Curves</td>
      <td>Curves to compute convex hull</td>
    </tr>
  </tbody>

    <tbody>
    <tr>
      <td style="text-align:center;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/A_Centroid.png" alt="Centroid" style="height:25px; margin-bottom:5px;">
          <span>Centroid</span>
        </div>
      </td>
      <td>Analyze centroid of each closed curve</td>
      <td style="text-align:center;">C</td>
      <td>Curve</td>
      <td>Curves to compute convex hull</td>
      <td style="text-align:center;">C</td>
      <td>Curves</td>
      <td>Curves to compute convex hull</td>
    </tr>
  </tbody>

</table>


The show's format consists of a combination of commercial television production elements and techniques which have evolved to reflect changes in American culture and audiences' viewing habits. It was the first children's TV show to use educational goals and a curriculum to shape its content, and the first show whose educational effects were formally studied. Its format and content have undergone significant changes over the years to reflect changes to its curriculum.

## Design
The show's format consists of a combination of commercial television production elements and techniques which have evolved to reflect changes in American culture and audiences' viewing habits. It was the first children's TV show to use educational goals and a curriculum to shape its content, and the first show whose educational effects were formally studied. Its format and content have undergone significant changes over the years to reflect changes to its curriculum.

<table style="width:100%; table-layout:auto; border-collapse: collapse;">

  <thead>
    <tr>
      <th style="text-align:center;">Tool</th>
      <th style="text-align:center;">Function</th>
      <th style="text-align:center;">Initial</th>
      <th style="text-align:center;">Name</th>
      <th style="text-align:center;">Description</th>
      <th style="text-align:center;">Initial</th>
      <th style="text-align:center;">Name</th>
      <th style="text-align:center;">Description</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td style="text-align:center;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/A_Centroid.png" alt="Centroid" style="height:25px; margin-bottom:5px;">
          <span>Centroid</span>
        </div>
      </td>
      <td>Analyze centroid of each closed curve</td>
      <td style="text-align:center;">C</td>
      <td>Curve</td>
      <td>Curves to compute convex hull</td>
      <td style="text-align:center;">C</td>
      <td>Curves</td>
      <td>Curves to compute convex hull</td>
    </tr>
  </tbody>

  <tbody>
    <tr>
      <td style="text-align:center;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/A_Centroid.png" alt="Centroid" style="height:25px; margin-bottom:5px;">
          <span>Centroid</span>
        </div>
      </td>
      <td>Analyze centroid of each closed curve</td>
      <td style="text-align:center;">C</td>
      <td>Curve</td>
      <td>Curves to compute convex hull</td>
      <td style="text-align:center;">C</td>
      <td>Curves</td>
      <td>Curves to compute convex hull</td>
    </tr>
  </tbody>

    <tbody>
    <tr>
      <td style="text-align:center;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/A_Centroid.png" alt="Centroid" style="height:25px; margin-bottom:5px;">
          <span>Centroid</span>
        </div>
      </td>
      <td>Analyze centroid of each closed curve</td>
      <td style="text-align:center;">C</td>
      <td>Curve</td>
      <td>Curves to compute convex hull</td>
      <td style="text-align:center;">C</td>
      <td>Curves</td>
      <td>Curves to compute convex hull</td>
    </tr>
  </tbody>

</table>


The show's format consists of a combination of commercial television production elements and techniques which have evolved to reflect changes in American culture and audiences' viewing habits. It was the first children's TV show to use educational goals and a curriculum to shape its content, and the first show whose educational effects were formally studied. Its format and content have undergone significant changes over the years to reflect changes to its curriculum.