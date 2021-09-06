# testdemo1

Here is the new line, just checking adding in this line for demo   

Here is the new line again

test line 3 for demo

* Unordered List Iteam
* Another Line
  * Sub Item
    * 1
    * 2
* Last Unordered Item

1. Item 1
2. Item 2
3. Item 3

---

This is demo line break
---

Including the link in line

[Google](https://www.google.com)

Showing the Link <https://wwww.google.com>

---

Including the images

![GoogleLogo](https://user-images.githubusercontent.com/89414582/132048440-e54d9a0f-a865-41f3-9446-6724b095551a.png)

Escape_Characters_testdemo

Escape\_Characters\_testdemo

---

* Directions for traveling from Maryville to Vemullapalli.
  1. Catch a Cab from Maryville to Kansas-city Airport.
  2. Take a flight to Chicago and catch the connecting flight to Hyderabad, India.
  3. Come out from the airport and catch a Airport Bus to MGBS.
  4. From MGBS, change to other bus to vemullapalli.
* list of items to be purchased:
  * Groceries:
    * Rice
    * Vegetables
    * Snacks
    * Meat
  * Drinks:
    * Mocktails
    * Wine
    * Beer
  * Grill Set.
  * Outdoor Tent Set with Chairs.

```
    private String laptopBrand;
    private String processor;
    private String operatingSystem;
    private int hardDrive;
    private double display;
    private boolean touch;

    /**
     * Parameterized Constructor for Laptop Class
     *
     * @param laptopBrand
     * @param processor
     * @param operatingSystem
     * @param hardDrive
     * @param display
     * @param touch
     */
    public Laptop(String laptopBrand, String processor, String operatingSystem, int hardDrive, double display, boolean touch) {
        this.laptopBrand = laptopBrand;
        this.processor = processor;
        this.operatingSystem = operatingSystem;
        this.hardDrive = hardDrive;
        this.display = display;
        this.touch = touch;
    }

    /**
     * Default Constructor for Laptop Class
     */
    public Laptop() {

    }

    /**
     * toString Method to get all the values
     *
     * @return String Object Values
     */
    public String toString() {
        return "Laptop Brand: " + laptopBrand + "\nLaptop Processor: " + processor + "\nLaptop Operating System: " + operatingSystem + "\nLaptop Hard Drive: " + hardDrive + "\nLaptop Display: " + display + "\nLaptop Is Touch: " + touch;
    }

    /**
     * Getter method for LaptopBrand Value
     *
     * @return laptopBrand
     */
    public String getLaptopBrand() {
        return laptopBrand;
    }

    /**
     * Setter Method to LaptopBrand
     *
     * @param laptopBrand
     */
    public void setLaptopBrand(String laptopBrand) {
        this.laptopBrand = laptopBrand;
    }

    /**
     * Getter Method for Processor Value
     *
     * @return processor
     */
    public String getProcessor() {
        return processor;
    }

    /**
     * Setter Method to Processor
     *
     * @param processor
     */
    public void setProcessor(String processor) {
        this.processor = processor;
    }

    /**
     * Getter Method for OperatingSystem
     *
     * @return operatingSystem
     */
    public String getOperatingSystem() {
        return operatingSystem;
    }

    /**
     * Setter Method to operatingSystem
     *
     * @param operatingSystem
     */
    public void setOperatingSystem(String operatingSystem) {
        this.operatingSystem = operatingSystem;
    }

    /**
     * Getter Method to hardDrive
     *
     * @return hardDrive
     */
    public int getHardDrive() {
        return hardDrive;
    }

    /**
     * Setter Method for hardDrive
     *
     * @param hardDrive
     */
    public void setHardDrive(int hardDrive) {
        this.hardDrive = hardDrive;
    }

    /**
     * Getter Method to Display value
     *
     * @return display
     */
    public double getDisplay() {
        return display;
    }

    /**
     * Setter Method for display
     *
     * @param display
     */
    public void setDisplay(double display) {
        this.display = display;
    }

    /**
     * Getter Method for touch
     *
     * @return touch
     */
    public boolean isTouch() {
        return touch;
    }

    /**
     * Setter Method to touch value
     *
     * @param touch
     */
    public void setTouch(boolean touch) {
        this.touch = touch;
```
