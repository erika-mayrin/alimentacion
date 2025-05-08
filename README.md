import React from 'react';
import NutriNavbar from './components/NutriNavbar';
import HealthHero from './components/HealthHero';
import MenuPlanner from './components/MenuPlanner';
import NutritionRecoveryPlans from './components/NutritionRecoveryPlans';
import WeeklyMenus from './components/WeeklyMenus';
import HealthyRecipes from './components/HealthyRecipes';
import NutriFooter from './components/NutriFooter';

const App = () => {
  return (
    <div className="min-h-screen flex flex-col">
      <NutriNavbar />
      <main className="flex-grow">
        <HealthHero />
        <div id="menu-planner">
          <MenuPlanner />
        </div>
        <NutritionRecoveryPlans />
        <WeeklyMenus />
        <HealthyRecipes />
      </main>
      <NutriFooter />
    </div>
  );
};

export default App;

// DONE
