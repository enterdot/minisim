## **🔍 C++ Structure**

1. **Base Controllers (from src/onthepitch/player/controller/):**
   - `icontroller.hpp/cpp` - Interface for all controllers
   - `playercontroller.hpp/cpp` - Base player controller class
   - `elizacontroller.hpp/cpp` - **Main AI brain** (what we've been working with)
   - `humancontroller.hpp/cpp` - Human input controller
   - `refereecontroller.hpp/cpp` - Referee AI

2. **Strategy System (src/onthepitch/player/controller/strategies/):**
   - `strategy.hpp/cpp` - Base strategy interface
   - **Off-the-ball strategies:**
     - `default_def.hpp/cpp` - **Defense strategy**
     - `default_mid.hpp/cpp` - **Midfield strategy** 
     - `default_off.hpp/cpp` - **Offense strategy**
     - `goalie_default.hpp/cpp` - **Goalkeeper strategy**

3. **AI Support System (src/onthepitch/AIsupport/):**
   - `AIfunctions.hpp/cpp` - **Core AI utility functions**
   - `mentalimage.hpp/cpp` - **Game state perception**

4. **Team Coordination:**
   - `teamAIcontroller.hpp/cpp` - **Team-level AI coordination**
