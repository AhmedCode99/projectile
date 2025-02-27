# Projectile Motion with Air Resistance 

### Projectile Motion:
A fundamental idea in physics known as "projectile motion" describes how an object launched into the air would move under the effect of gravity when it is near the Earth's surface. In projectile motion, an object moves along a curved route or trajectory as a result of the combined forces of gravity acting on it and its starting velocity. There are two perpendicular parts to this motion: horizontal motion and vertical motion.

### Projectile Motion with Air Resistance:
Compared to the idealized case where there is no air resistance, the reality of projectile motion is more complicated. When air resistance is taken into account, a further force that opposes the projectile's travel through the air influences its motion. This force is normally in the opposite direction of the projectile's motion and inversely proportional to the square of the projectile's velocity.

The primary consideration in projectile motion with air resistance is the **drag force (F_d)**.A projectile is thrown into the air. The drag force acting on the projectile will slow it down until it eventually stops and falls back to the ground. The drag coefficient of the projectile depends on its shape and size. For example, a baseball has a higher drag coefficient than a golf ball, so it will slow down more quickly. 
The drag force is given by the equation:

F_d = -k * v^2

Where:

- F_d is the drag force.
- k is the drag coefficient, which depends on the shape and size of the object.
- v is the magnitude of the velocity of the projectile.

### Here are the key principles and equations that govern projectile motion:

1. Initial Velocity (V₀): The object is given an initial velocity V₀ at some angle θ above the horizontal.

2. Gravity (g): Gravity acts vertically downward with an acceleration of approximately 9.81 m/s² (on Earth). This acceleration affects the vertical motion of the projectile.

3. Horizontal Motion: In the absence of air resistance, there is no horizontal force acting on the object once it is launched. As a result, the horizontal velocity (Vx) remains constant throughout the motion.

4. Vertical Motion: The vertical motion is influenced solely by the force of gravity. The vertical velocity (Vy) changes as the object rises and falls.

The equations that describe projectile motion in idealized condition (i.e. **no air resistance**) are as follows:

**Horizontal Motion:**

- Distance traveled in the horizontal direction (range, R) is given by: R = (V₀² * sin(2θ)) / g

**Vertical Motion:**

- The maximum height (H) reached by the projectile is given by: H = (V₀² * sin²(θ)) / (2 * g)
- The time of flight (T) is the total time the projectile is in the air and is given by: T = (2 * V₀ * sin(θ)) / g
- The vertical position (y) at any time (t) is given by: y = V₀ * sin(θ) * t - (1/2) * g * t²



The equations governing projectile motion with air resistance become differential equations, and their solutions typically require numerical methods. The equations of motion in this case are:

The equations governing projectile motion with air resistance become differential equations, and their solutions typically require numerical methods. The equations of motion in this case are:

**Horizontal motion:**
\[F_{dx} = -k * V_x * |V_x|\]

Where:
- \(F_{dx}\) is the horizontal component of the drag force.

**Vertical motion:**
\[F_{dy} = -mg - k * V_y * |V_y|\]

Where:
- \(F_{dy}\) is the vertical component of the drag force.

The equations for \(V_x\) and \(V_y\) become:

\[V_x = V_{0x} - \frac{k * V_x * |V_x|}{m} * \Delta t\]
\[V_y = V_{0y} - \left(g + \frac{k * V_y * |V_y|}{m}\right) * \Delta t\]

Here,
- \(V_{0x}\) and \(V_{0y}\) are the initial horizontal and vertical velocities,
- \(m\) is the mass of the projectile,
- \(g\) is the acceleration due to gravity, and
- \(\Delta t\) is the time step used in numerical integration.
