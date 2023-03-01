
- Kinematics
	- Tools:
		- Graph of position, delta
		- The graph of velocity versus time
		- 4 kinematics equations 
			- (only 1 equation is time-independent, which is specialized for calculating shooting range, maximum height. 3 other equations are time-dependent, which describes the in-motion object.)
			- Explanation: Given any kinematic equation, if there is $t$ exists, we can substitute $t = f(v,u,t)$ to a specific equation. After substituting variable $t$ into the equation, we say that equation is now independent to that variable.
			- In math, we denote it as: 
				- 1. $v = u  + at$, $t = \frac{v-u}{a}$
				- 2. $\Delta s = v_i t + \frac{1}{2}at^2$
				- 3. $\Delta s = v_i [t \rightarrow \frac{v-u}{a}] + \frac{1}{2}a[\frac{v-u}{a}]^2$
				- 4. $v^2 - u^2 = 2as$
```json
{
  "kinematics": {
    "definitions": {
      "displacement": "The change in position of an object.",
      "velocity": "The rate at which an object changes its position.",
      "acceleration": "The rate at which an object changes its velocity."
    },
    "equations": {
      "average_velocity": "v = ∆x/∆t",
      "average_acceleration": "a = ∆v/∆t",
      "displacement": "∆x = v*t",
      "final_velocity": "v_f = v_i + a*t",
      "displacement_with_acceleration": "∆x = v_i*t + 1/2*a*t^2",
      "final_velocity_squared": "v_f^2 = v_i^2 + 2*a*∆x"
    },
    "units": {
      "displacement": "meters (m)",
      "velocity": "meters per second (m/s)",
      "acceleration": "meters per second squared (m/s^2)"
    },
    "examples": [
      {
        "problem": "A car travels 50 meters in 10 seconds. What is its average velocity?",
        "solution": "v = ∆x/∆t = 50m/10s = 5 m/s"
      },
      {
        "problem": "A car starts from rest and reaches a velocity of 20 m/s in 5 seconds. What is its acceleration?",
        "solution": "a = ∆v/∆t = (20 m/s - 0 m/s)/5 s = 4 m/s^2"
      },
      {
        "problem": "A ball is thrown straight up with an initial velocity of 20 m/s. How long does it take to reach its maximum height?",
        "solution": "v_f = v_i + a*t = 0 m/s. Solving for t, we get t = v_i/a = 20 m/s / 9.8 m/s^2 = 2.04 s"
      }
    ]
  }
}
```

- Force 
```json
{
  "force": {
    "definition": "Force is a push or pull upon an object resulting from the object's interaction with another object.",
    "formula": {
      "Newton's Second Law": "F = ma"
    },
    "types": {
      "Contact force": [
        "Frictional force",
        "Tension force",
        "Normal force",
        "Air resistance force"
      ],
      "Non-contact force": [
        "Gravitational force",
        "Electromagnetic force"
      ]
    },
    "laws": {
      "Newton's First Law": "An object at rest tends to stay at rest, and an object in motion tends to stay in motion with the same speed and in the same direction, unless acted upon by an unbalanced force.",
      "Newton's Second Law": "The acceleration of an object is directly proportional to the net force acting on the object, and inversely proportional to its mass. F = ma",
      "Newton's Third Law": "For every action, there is an equal and opposite reaction."
    },
    "units": {
      "SI unit": "Newton (N)",
      "Other units": [
        "Pound-force (lbf)",
        "Dyne (dyn)"
      ]
    }
  }
}
```

- Projectile motion
	- Assumptions of projectile motion calculations:
		- Air resistance is negligible
		- Gravitational force is constant and uniform
	- Calculations
		- Decompose the speed vectors into 2 parts, by trigonometric functions.
	- Horizontal displacement
	- Maximum height, Range (independent of time)
```json
{
"title": "Projectile Motion",
"topics": [
{
"title": "Overview",
"content": "Projectile motion is the motion of an object that has been launched into the air and is subject to the force of gravity. It is a form of two-dimensional motion that can be broken down into horizontal and vertical components."
},
{
"title": "Equations of Motion",
"content": "The equations of motion for projectile motion are:\n- Vertical displacement: d_y = v_{i,y}t + 0.5at^2\n- Horizontal displacement: d_x = v_{i,x}t\n- Vertical velocity: v_y = v_{i,y} + at\n- Horizontal velocity: v_x = v_{i,x}\n- Time of flight: t = 2v_{i,y}/g\n- Maximum height: h = v_{i,y}^2/2g\n- Range: R = v_{i}^2*sin(2\theta)/g"
},
{
"title": "Assumptions",
"content": "Projectile motion assumes that:\n- Air resistance is negligible\n- The gravitational force is constant and uniform\n- The object is launched on a level surface\n- The Earth is flat"
},
{
"title": "Examples",
"content": "Examples of projectile motion include:\n- A ball being thrown\n- A bullet being fired\n- A rocket being launched\n- A stone being catapulted"
},
{
"title": "Applications",
"content": "Projectile motion has many applications in the real world, including:\n- Sports such as basketball, football, and baseball\n- Fireworks displays\n- Military operations such as artillery fire\n- Space travel and satellite launches"
}
]
}
```
