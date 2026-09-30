#include <iostream>
#include <string>

using namespace std;

// Function to display the main interactive menu
void showMenu() {
    cout << "\n======================================================\n";
    cout << "   NUCOR STEEL PRODUCT EVOLUTION & MARKET RECOMMENDER   \n";
    cout << "     (Inspired by Clayton Christensen's Disruptive Model)\n";
    cout << "======================================================\n";
    cout << "Select a target market tier / product category:\n";
    cout << "1. Low-End Construction (Rebar / Reinforcing Bars)\n";
    cout << "2. Medium-Grade Structural Steel (Wide-Flange Beams)\n";
    cout << "3. High-Grade Sheet Steel (Thin-Slab Flat-Rolled Steel)\n";
    cout << "4. Exit Program\n";
    cout << "------------------------------------------------------\n";
    cout << "Enter your choice (1-4): ";
}

int main() {
    int choice;
    do {
        showMenu();
        cin >> choice;

        // Input validation check
        if (cin.fail()) {
            cin.clear(); // Clear error flags
            cin.ignore(10000, '\n'); // Discard invalid input
            cout << "\n[Error] Invalid input. Please enter a valid number between 1 and 4.\n";
            continue;
        }

        switch (choice) {
            case 1: {
                cout << "\n--- Tier 1: Low-End Construction (Rebar) ---\n";
                cout << "Product Application : Residential/commercial construction concrete reinforcement.\n";
                cout << "Production Method   : Electric Arc Furnace (EAF) melting scrap steel.\n";
                cout << "Economic Advantage  : ~20% cost reduction and no legacy blast-furnace asset burden.\n";
                cout << "Disruption Insight  : Rebar generated low gross margins (~7%) for traditional integrated mills, "
                     << "giving incumbents a weak incentive to defend it. Mini-mills established a secure low-end foothold here.\n";
                break;
            }
            case 2: {
                cout << "\n--- Tier 2: Medium-Grade Structural Steel ---\n";
                cout << "Product Application : Skyscraper frameworks, bridges, and industrial building framing.\n";
                cout << "Production Method   : Advanced EAF long-product rolling (e.g., Nucor-Yamato joint venture).\n";
                cout << "Economic Advantage  : Expanded capability beyond basic rebar into higher-load structural shapes.\n";
                cout << "Disruption Insight  : As process capabilities improved, mini-mills moved upmarket, "
                     << "capturing more demanding construction segments previously dominated by integrated steelmakers.\n";
                break;
            }
            case 3: {
                cout << "\n--- Tier 3: High-Grade Sheet Steel ---\n";
                cout << "Product Application : Automotive body panels, home appliances, pipes, and tubing.\n";
                cout << "Production Method   : Compact Strip Production (CSP) / Thin-slab casting.\n";
                cout << "Economic Advantage  : High-volume flat-rolled production with compact capital exposure.\n";
                cout << "Disruption Insight  : Reached mainstream disruption. Nucor pioneered EAF thin-slab casting "
                     << "to enter flat-rolled sheet markets, eventually overtaking legacy incumbents to become a top industry leader.\n";
                break;
            }
            case 4:
                cout << "\nExiting Nucor Recommender System. Thank you for exploring Christensen's model!\n";
                break;
            default:
                cout << "\n[Error] Invalid selection. Please choose an option from 1 to 4.\n";
        }

    } while (choice != 4);

    return 0;
}
