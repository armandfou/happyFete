<?php
namespace AppBundle\Entity;
use Doctrine\ORM\Mapping as ORM;
/** 
 * @ORM\Entity
 * @ORM\Table(name="feteTb")
 */    
    
class feteTb
{
    /**
     * @ORM\Column(type="integer")
     * @ORM\Id 
     * @ORM\GeneratedValue (strategy="AUTO")
     */
    protected $id;
    /**
     * @ORM\Column(type="string", length=100)
     */

	protected $name;
    /**
     * @ORM\Column(type="text")
     */

	protected $desc;

    /**
     * @ORM\Column(type="datetime", name="date")
     */
 
	protected $date;
    
    /**
     * @ORM\Column(type="string", length=100)
     */
    
	protected $artist;
    /**
     * @ORM\Column(type="string", length=100)
     */

    protected $lieu;

    /**
     * @ORM\Column(type="string", length=255)
     */

	protected $picture;

    
    /**
     * Get id
     *
     * @return integer
     */
    public function getId()
    {
        return $this->id;
    }

    /**
     * Set name
     *
     * @param string $name
     *
     * @return feteTb
     */
    public function setName($name)
    {
        $this->name = $name;

        return $this;
    }

    /**
     * Get name
     *
     * @return string
     */
    public function getName()
    {
        return $this->name;
    }

    /**
     * Set desc
     *
     * @param string $desc
     *
     * @return feteTb
     */
    public function setDesc($desc)
    {
        $this->desc = $desc;

        return $this;
    }

    /**
     * Get desc
     *
     * @return string
     */
    public function getDesc()
    {
        return $this->desc;
    }

    /**
     * Set date
     *
     * @param \DateTime $date
     *
     * @return feteTb
     */
    public function setDate($date)
    {
        $this->date = $date;

        return $this;
    }

    /**
     * Get date
     *
     * @return \DateTime
     */
    public function getDate()
    {
        return $this->date;
    }

    /**
     * Set artist
     *
     * @param string $artist
     *
     * @return feteTb
     */
    public function setArtist($artist)
    {
        $this->artist = $artist;

        return $this;
    }

    /**
     * Get artist
     *
     * @return string
     */
    public function getArtist()
    {
        return $this->artist;
    }

    /**
     * Set lieu
     *
     * @param string $lieu
     *
     * @return feteTb
     */
    public function setLieu($lieu)
    {
        $this->lieu = $lieu;

        return $this;
    }

    /**
     * Get lieu
     *
     * @return string
     */
    public function getLieu()
    {
        return $this->lieu;
    }

    /**
     * Set picture
     *
     * @param string $picture
     *
     * @return feteTb
     */
    public function setPicture($picture)
    {
        $this->picture = $picture;

        return $this;
    }

    /**
     * Get picture
     *
     * @return string
     */
    public function getPicture()
    {
        return $this->picture;
    }
}
